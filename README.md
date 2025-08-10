# Advertising sales prediction with linear regression

## 개요
- **목표:** TV, Radio, Newspaper, 광고비 데이터를 기반으로 제품 판매량을 예측하는 **선형회귀** 모델을 구현
- **알고리즘:** Linear regression
- **핵심 포인트:**
  - statsmodels, sklearn linear regression
  - 회귀분석결과 지표를 보고 모델 성능 해석하기
  - 선형성, 등분산성, 정규성 확인하고 특징 파악하기

## 사용 데이터
- **Dataset**: [Advertising Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset)
- 주요 변수:
  - `TV`: TV 광고비
  - `Radio`: 라디오 광고비
  - `Newspaper`: 신문 광고비
  - `Sales`: 제품 판매량

## 분석과정
1. 데이터 로드 및 탐색(EDA)
2. 광고비와 판매량의 관계 시각화
3. 단순/다중 선형회귀 모델 학습
4. 모델 성능평가
5. 잔차 체크
6. 다중공산성 확인

## 실행 방법
1. `advertising.ipynb` 실행

## 프로젝트 파일 구조
ADVERTISING/
├─ data/  
├─ utils/  
├─ .gitattributes  
├─ .gitignore  
├─ advertising.ipynb  
├─ README.md  
└─ requirements.txt  

## 결과물
- 데이터 로드 및 target 변수와 각 변수간의 상관관계 파악
- 단순선형회귀 - Statsmodels, Sklearn
- 다중선형회귀 - LinearRegression, Lasso
- Residuals 분석
- 다중공산성 확인
- ROI 비교