# Parkinson's Disease Progression Prediction Project<br/>(2023.04.24 ~ 2023.05.17)
<br/>

## [1. Streamlit Service](https://yulminsung-forestfire-app-b2m0vk.streamlit.app/ "Streamlit Link")<br/>

## [2. Personal Code](https://github.com/YulminSung/Project_Forestfire/tree/main/code ".Code Link")<br/>

## [3. Machine Learning](https://github.com/YulminSung/Project_Forestfire/blob/main/code/DL_EfficientNet.ipynb/ ".DL Link")<br/>

## [4. PDF](https://github.com/YulminSung/Project_Forestfire/blob/main/file/ppt/ForestFire.pdf "PDF Link")<br/>

---

## ✔ 목적
1. 파킨슨병 환자의 **임상 데이터**를 사용하여 파킨슨병 환자의 진행을 측정하는 **MDS-UPDRS (통합 파킨슨병 평가척도) 예측**<br/><br/>
2. streamlit을 활용한 **대시보드 웹 개발**
<br/>

## ✔ 데이터
**Kaggle Competition - AMP®-Parkinson's Disease Progression Prediction**에서 제공한 데이터를 이용

[AMP®-Parkinson's Disease Progression Prediction](https://www.kaggle.com/competitions/amp-parkinsons-disease-progression-prediction)
<br/>

## ✔ ERD
![screensh](img/erd.png)
<br/>

## ✔ Flow Chart
![image](https://github.com/YulminSung/Project_Parkinson/blob/main/img/flowchart.png)
<br/>

## ✔ 팀 구성
- 사용언어 : Python
- 작업툴 : VS Code / PyCharm / Google Colab / Google BigQuery / QGIS / IBM SPSS Statistics
- 인원 : 3명
- 주요 업무 : 머신러닝을 활용한 파킨슨병 환자 진행 예측 및 Streamlit 라이브러리를 이용한 웹개발 구현 코드 작성
- 기간 : 2023.05.22 ~ 2023.06.23

## ✔ 대시보드 주요 기능
- **HOME**
  - 대회 목표 및 개요

<img src="/img/home.png" width="450" height="500">

- **Description**
  - 파킨슨병 / MDS-UPDRS 점수 설명
  - 평가지표 설명
  - 대회에 사용되는 용어 설명

<img src="/img/description.png" width="450" height="500">

- **Data**
  - 데이터셋 변수 설명
  - Train / Test 데이터셋 확인

<img src="/img/data.png" width="450" height="500">

- **EDA**
  - 방문 월 - Updrs 1~4 점수 평균 산점도/꺽은선그래프 시각화
  - 결측치 확인을 위한 파이그래프 시각화
  - 약물복용여부에 따른 updrs 점수 박스플롯 시각화

<img src="/img/eda.png" width="450" height="500">

- ***통계분석(STAT)***
    - 기초통계 분석 - 두 평균의 비교 (t-test) 설명
    - 귀무/대립 가설 설정 및 결론
    - 약물복용여부(On, Off) 두 그룹 간 평균 비교 박스플롯 시각화
    - visit_month - updrs 1~4 사이의 회귀분석 및 산점도/회귀선 시각화 (기초통계분석 포함)
    - 전체 데이터의 컬럼 간 상관관계 분석
    - 평가지표 간 점수 비교 (updrs 4 기준)

<img src="/img/stat.png" width="450" height="500">

- ***머신러닝(ML)***
    - CatBoost 모델 및 파라미터 설명
    - 훈련 / 검증 데이터 분리 및 확인
    - 모델 성능평가 결과 비교

<img src="/img/ml.png" width="450" height="500">

---

## 대회 결과 🏆
- **최종 점수 : 56.0점**
- **1,788팀 중 450등** (상위 약 25 %)

---

## 설치 방법
### Windows
- **프로젝트 파일을 다운로드 받습니다.** 

```bash
git clone https://github.com/YulminSung/Parkinson_1.git
```

- **프로젝트 경로에서 가상환경 설치 후 접속합니다. (Windows 10 기준)**
```bash
virtualenv venv
source venv/Scripts/activate
```

- **라이브러리를 설치합니다.** 
```bash
pip install -r requirements.txt
```

- **streamlit 명령어를 실행합니다.** 
```bash
streamlit run app.py
```