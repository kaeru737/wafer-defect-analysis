\# Wafer Defect Analysis



웨이퍼 맵 데이터를 활용하여 반도체 불량 패턴을 분석하고, 주요 불량 유형을 분류하는 데이터 분석 프로젝트입니다.



\## 프로젝트 개요



이 프로젝트는 WM-811K 웨이퍼 맵 데이터를 기반으로 불량 유형별 패턴을 시각화하고, 파생변수를 생성하여 머신러닝 모델로 불량 유형을 분류하는 것을 목표로 합니다.



\## 분석 목표



\- 웨이퍼 불량 유형별 데이터 분포 확인

\- 불량 패턴 시각화

\- 불량 위치 및 비율 기반 파생변수 생성

\- 주요 불량 클래스 선정

\- 머신러닝 모델을 활용한 불량 유형 분류

\- Confusion Matrix 및 Classification Report 기반 성능 평가



\## 사용 데이터



\- WM-811K Wafer Map Dataset

\- 원본 데이터 파일(`LSWMD.pkl`)은 용량 및 데이터 출처 문제로 저장소에 포함하지 않았습니다.

\- 실행 시 `data/LSWMD.pkl` 경로에 데이터 파일을 별도로 추가해야 합니다.



\## 사용 기술



\- Python

\- pandas

\- numpy

\- matplotlib

\- scikit-learn

\- Jupyter Notebook



\## 프로젝트 구조



```text

wafer-defect-analysis

├── notebooks

│   └── wafer\_defect\_analysis.ipynb

├── data

│   └── .gitkeep

├── figures

├── .gitignore

└── README.md

