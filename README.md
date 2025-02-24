
# 🏥 Prediabetes Prediction Model

## 📌 개요
**CatBoost와 XGBoost를 앙상블하여 이진 분류 문제를 해결**하는 모델입니다.  
Optuna를 이용해 **하이퍼파라미터 튜닝**을 수행하며, Stratified K-Fold 교차 검증을 사용합니다.

## 🛠️ 사용된 기술
- **OS:** macOS 15.3.1
- **프로그래밍 언어:** Python
- **주요 라이브러리:** CatBoost, XGBoost, scikit-learn, Optuna, pandas, numpy
- **하이퍼파라미터 튜닝:** Optuna
- **교차 검증:** Stratified K-Fold

---

## 🔧 설치 방법
프로젝트 실행을 위해 아래 패키지를 설치해야 합니다.
```bash
pip install -r requirements.txt
```

## 📂 프로젝트 구조
```
이 프로젝트는 다음과 같은 파일과 폴더로 구성됩니다.
📂 프로젝트 폴더
 ├── 📜 preprocessing.py        # 데이터 전처리 스크립트
 ├── 📜 custom_catboost.py      # CatBoost 모델 커스텀 클래스
 ├── 📜 custom_xgboost.py       # XGBoost 모델 커스텀 클래스
 ├── 📜 main_script.ipynb       # Jupyter Notebook에서 실행하는 메인 스크립트 
 ├── 📜 requirements.txt        # 필요한 패키지 목록
 ├── 📜 README.md               # 프로젝트 설명 파일 (현재 문서)
 ├── 📂 data                    # 원본 및 처리된 데이터 저장 폴더
 │   ├── train.csv              # 학습 데이터
 │   ├── test.csv               # 테스트 데이터
 │   ├── new_data.csv           # 새로운 예측용 데이터
 │   └── submission.csv         # 예측 결과 저장
 └── 📂 results                 # 모델 평가 결과 저장
```

# 📜 이은호 포트폴리오
> 이은호(Eunho Lee) - eunnnholee 포트폴리오
>> 꿈 보다는 야망이라는 단어를 더 선호하는 지원자
<br/>

[Eunho_Lee_Portfolio](https://github.com/eunnnholee/Portfolio/blob/main/%E1%84%91%E1%85%A9%E1%84%90%E1%85%B3%E1%84%91%E1%85%A9%E1%86%AF%E1%84%85%E1%85%B5%E1%84%8B%E1%85%A9_%E1%84%8B%E1%85%B5%E1%84%8B%E1%85%B3%E1%86%AB%E1%84%92%E1%85%A9.pdf)

<br/>


# 🔎 Profile

> 학력
  - 연세대학교 패키징 및 물류학과  2019.03 - 2023.03
  - 연세대학교 산업공학과[이중전공] 2023.03 - 2024.08 (졸업)

<br/>

> 경력 및 대외활동
  - 연세대학교 패키징 물류 연구실 학부 인턴 2022.09 - 2022.12
  - 한국장학재단 대학튜터링 2022.09 - 2023.02

<br/>

> 교육
  - LGAimers 4기 수료
  - LGAimers 5기 수료

<br/>

> 자격증 및 어학
  - 컴퓨터활용능력 1급   2023.06
  - 데이터분석 준전문가(ADsP)   2023.06
  - SQL 개발자(SQLD)  2024.04
  - 빅데이터분석기사  2024.07
  - OPIc IM1 2024.07

<br/>

> 수상정보
  - 동서발전 풍력발전량 예측 공모전 본선 진출 (6위 이내)
  - 데이터마이닝 우수작품 선정 (교내)
  - 공공데이터 기반 청소년 상담보직사업 국민 아이디어 공모전 (이사장상)

<br/>
<br/>

# 📝 Projects
프로젝트 순서는 모델링 프로젝트, 기획 프로젝트 순으로 작성되었습니다.

<br/>

## **1. 👶 육아지원정책: KoBERTopic과 SNA를 통한 심층 분석**
> 요약
- 산발적으로 흩어져 있는 육아휴직 관련 정보를 7개의 새로운 질문지로 재구성 (텍스트데이터 약 4000개 -> 7개 질문지)

> 역할
- 총 3명이 함께 진행
- 팀장, 크롤링 및 텍스트마이닝, SNA 방법론 제안 및 노드와 엣지 설계

> 성과
- 교내 우수작품 선정
  
> 시기
- 2023.03 - 2023.06

[프로젝트 상세 설명](https://github.com/eunnnholee/childcare-policy-KoBERTopic-SNA)

<br/>
<br/>


## **2. 👩‍🦯 시각장애인을 위한 보조 기능 - Image Captioning**
> 요약
- 시각장애인을 위한 보조 기능으로서의 이미지 캡셔닝 기술: 모델 비교 및 효용성 평가

> 역할
- 총 4명이 함께 진행
- Transfomer 및 InceptionV3 구조 제안 및 모델 설계
  
> 시기
- 2023.10 - 2023.11

[프로젝트 상세 설명](https://github.com/eunnnholee/vision-aid-image-captioning)

<br/>
<br/>

## **3. 🎉 지역 균형 발전을 위한 지역축제 만족도 개선 연구 : 토픽 모델링과 QFD를 중심으로**
> 요약
- 토픽모델링을 통해 도출된 키워드를 조합해 QFD를 작성하고 산출된 중요도를 지역 축제 요구품질 중요도로 설정하여, 지역축제의 만족도를 개선하고 본래의 문제를 해결

> 역할
- 총 3명이 함께 진행
- 팀장, 프로젝트의 모든 코딩 작업 수행 및 HOQ 구성
  
> 시기
- 2023.10 - 2023.11

[프로젝트 상세 설명](https://github.com/eunnnholee/Regional-Festival-Satisfaction-Improvement)


<br/>
<br/>

## **4. 👕 무신사 기업 현황 분석 및 문제 해결을 위한 기획**
> 요약
- 2030 타겟 공략을 위한 전략 : 경쟁사와의 차별화
- 타 기업의 솔루션을 벤치마킹하여 무신사 시스템에 적용

> 역할
- 총 3명이 함께 진행
- 팀장, 무신사의 문제점 도출 및 기업이 내세운 전략을 기반으로 차별화 전략 도출 : 사용자 시안 공모 및 제작 서비스
  
> 시기
- 2024.05 - 2024.06
  
[프로젝트 상세 설명](https://github.com/eunnnholee/musinsa-analysis-solutions)

<br/>
<br/>

## **5. 🙆‍♂️ 공공데이터 기반 청소년상담복지사업 국민 아이디어 공모전**
> 요약
- 청소년 상담 센터 유입 향상을 위한 '마음 치유 약국'

> 역할
- 총 4명이 함께 진행
- 데이터 분석을 통한 아이디이 제안
  
> 시기
- 2023.03 - 2023.05
  
[프로젝트 상세 설명](https://github.com/eunnnholee/Youth-Welfare-Data-Analysis)
