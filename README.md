# Parkinson Project (2023.04.24 ~ 2023.05.17)

[대시보드 링크](https://yulminsung-parkinson-1-app-7xcgv0.streamlit.app/) <br/><br/>
[발표 영상] <br/><br/>
[데모 시연] <br/><br/>
[포트폴리오](https://github.com/YulminSung/Parkinson_1/tree/059eb9e34efac9167f72358b9c93ec2420ba6f77/pdf)<br/><br/>
![screensh](img/홈페이지.png)

## 목적
계약일 기준 2022년 1월 1일부터 현재까지의 **서울시 전/월세 실거래 데이터 기반 검색** 및 **전세 시세 예측** 웹 개발

## 데이터
서울 열린데이터 광장 - 서울시 부동산 전월세가 정보 공공 데이터를 이용하였습니다.

[서울시 부동산 전월세가 정보](https://data.seoul.go.kr/dataList/OA-21276/S/1/datasetView.do)

## ERD
![screensh](img/erd.png)

## 팀 구성
- 사용언어 : Python : 3.9.13v
- 작업툴 : Pycharm, Google Colab, Streamlit
- 인원 : 3명
- 주요 업무 : Streamlit 라이브러리를 이용한 웹개발 구현 코드 작성 및 머신러닝을 활용한 전세 시세 예측
- 기간 : 2023-04-24 ~ 2023-05-17
***

## 주요 기능
- 홈페이지(Home)
    - 대회 목표 및 개요
- 설명(Description)
    - 파킨슨병 / MDS-UPDRS 점수 설명
    - 평가지표 설명
    - 대회에 사용되는 용어 설명
- 데이터(Data)
    - 데이터셋 컬럼별 설명
    - Train / Test 데이터 확인
- 탐색적자료분석(EDA)
    - 임상데이터, 보충 임상데이터, 단백질데이터, 펩타이드데이터 구분하여 sidebar.selectbox 구성
    - 방문 월 - Updrs 1~4 점수 평균 비교 월세 월평균 추이 꺾은선그래프 시각화
    - 월세, 전세 실거래 수 지역 순위 막대그래프 시각화
    - 지역구 선택 후 전세 예측 모델 시각화
    - 게시판 작성자, 이메일, 제목, 내용 저장을 위한 db 구축
    - 문의 내용 작성칸 구축
    - 게시판 목록 구현
    - 관리자모드
    - 처리상태 변경
- 통계분석(STAT)
    - 게시판 작성자, 이메일, 제목, 내용 저장을 위한 db 구축
    - 문의 내용 작성칸 구축
- 머신러닝(ML)
    - 게시판 작성자, 이메일, 제목, 내용 저장을 위한 db 구축
    - 문의 내용 작성칸 구축

## 설치 방법
### Windows
+ 버전 확인
    - python : 3.9.13
    - pycharm : 17.0.6
    - streamlit : 1.22.0
    - 라이브러리 :  pandas (2.0.1), numpy (1.24.3), plotly (5.14.1), plotly-express(0.4.1), matplotlib (3.7.1), streamlit-option-menu (0.3.2), seaborn (0.12.2), scikit-learn(1.2.2), pingouin(0.5.3), statmodels(0.13.5), utils(1.0.1), catboost(1.16.0) 

- 프로젝트 파일을 다운로드 받습니다. 

```bash
git clone https://github.com/YulminSung/Parkinson_1.git
```

- 프로젝트 경로에서 가상환경 설치 후 접속합니다. (Windows 10 기준)
```bash
virtualenv venv
source venv/Scripts/activate
```

- 라이브러리를 설치합니다. 
```bash
pip install -r requirements.txt
```

- streamlit 명령어를 실행합니다. 
```bash
streamlit run app.py
```