# Parkinson's Disease Progression Prediction Project<br/>(2023.04.24 ~ 2023.05.17)

> [대시보드 링크](https://yulminsung-parkinson-1-app-7xcgv0.streamlit.app/) <br/><br/>
> [발표 영상] <br/><br/>
> [데모 시연] <br/><br/>
> [포트폴리오](https://github.com/YulminSung/Parkinson_1/tree/059eb9e34efac9167f72358b9c93ec2420ba6f77/pdf)<br/><br/>
![screensh](img/홈페이지.png)

---

## 목적 🔍
> 파킨슨병 환자의 **임상 데이터**를 사용하여 파킨슨병 환자의 진행을 측정하는 **MDS-UPDRS (통합 파킨슨병 평가척도) 예측**<br/><br/>
> streamlit을 활용한 **대시보드 웹 개발**

---

## 데이터 📂
> **Kaggle Competition - AMP®-Parkinson's Disease Progression Prediction**에서 제공한 데이터를 이용하였습니다.

[Kaggle_대회_정보](https://www.kaggle.com/competitions/amp-parkinsons-disease-progression-prediction)

---

## E-R Diagram (Entity-Relationship Diagram) 📖
![screensh](img/erd.png)

---

## 팀 구성 👨🏻‍🤝‍👨🏻
> 개발 기간 : 2023-04-24 ~ 2023-05-17<br/><br/>
> 인원 : 3명<br/><br/>
> 주요 업무 : 머신러닝을 활용한 파킨슨병 환자 진행 예측 및 Streamlit 라이브러리를 이용한 웹개발 구현 코드 작성<br/><br/>

---

## Stacks 🐈

### Environment
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=PyCharm&logoColor=white)
![GoogleColab](https://img.shields.io/badge/GoogleColab-F9AB00?style=for-the-badge&logo=GoogleColab&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)             

### Development
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white)

### Library
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=Pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=Numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=Plotly&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=for-the-badge&logo=ScikitLearn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=Plotly&logoColor=white)

### Communication
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)

---

## 대시보드 주요 기능 ⚙
- ***홈페이지(Home)***
    - 대회 목표 및 개요<br/><br/>

- ***설명(Description)***
    - 파킨슨병 / MDS-UPDRS 점수 설명
    - 평가지표 설명
    - 대회에 사용되는 용어 설명<br/><br/>

- ***데이터(Data)***
    - 데이터셋 변수 설명
    - Train / Test 데이터셋 확인<br/><br/>

- ***탐색적자료분석(EDA)***
    - 방문 월 - Updrs 1~4 점수 평균 산점도/꺽은선그래프 시각화
    - 결측치 확인을 위한 파이그래프 시각화
    - 약물복용여부에 따른 updrs 점수 박스플롯 시각화<br/><br/>

- ***통계분석(STAT)***
    - 기초통계 분석 - 두 평균의 비교 (t-test) 설명
    - 귀무/대립 가설 설정 및 결론
    - 약물복용여부(On, Off) 두 그룹 간 평균 비교 박스플롯 시각화
    - visit_month - updrs 1~4 사이의 회귀분석 및 산점도/회귀선 시각화 (기초통계량 포함)
    - 전체 데이터의 컬럼 간 상관관계 분석
    - 평가지표 간 점수 비교 (updrs 4에 따라서)<br/><br/>

- ***머신러닝(ML)***
    - CatBoost 모델 및 파라미터 설명
    - 훈련 / 검증 데이터 분리 및 확인
    - 모델 성능평가 결과 비교<br/><br/>

---

## 대시보드 화면 구성 📺
| 메인 페이지  |  소개 페이지   |
| :-------------------------------------------: | :------------: |
|  <img width="329" src="https://user-images.githubusercontent.com/50205887/208036155-a57900f7-c68a-470d-923c-ff3c296ea635.png"/> |  <img width="329" src="https://user-images.githubusercontent.com/50205887/208036645-a76cf400-85bc-4fa2-af72-86d2abf61366.png"/>|  
| 강좌 소개 페이지   |  강의 영상 페이지   |  
| <img width="329" src="https://user-images.githubusercontent.com/50205887/208038737-2b32b7d2-25f4-4949-baf5-83b5c02915a3.png"/>   |  <img width="329" src="https://user-images.githubusercontent.com/50205887/208038965-43a6318a-7b05-44bb-97c8-b08b0495fba7.png"/>     |

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