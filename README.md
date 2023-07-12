# Temperature_Prediction

### 수행 기간 : 2023.03.13 - 2023.03.29

## 데이터 출처
- 기상 데이터: 기상청 기상자료개방포털
- 대기 정보 데이터: 에어코리아 홈페이지 크롤링
- 2018년1월1일00시~2022년12월31일23시 시간대별 데이터

## 사용한 언어 및 라이브러리
- Python
  - Pandas, Numpy, Matplotlib, BeautifulSoup, Selenium, statsmodels, keras
- R
  
## 데이터 분석
    
1. 회귀 분석
   - 각 변수(오존량, 미세먼지 농도, 풍속, 강수량 등)와 기온 간의 관계 단순 회귀 분석
   - 여러 변수와 기온 간의 다중 회귀 분석
   - 여러 모델(선형 회귀, 의사결정나무, RF, 인공신경망)을 활용한 기온 예측
    
2. 시계열 분석
   - 계절성이 존재하는 기온 데이터 차분
   - ARIMA(4,1,5) 모형으로 기온 예측


## 개선 방안

1. 회귀 분석
   - 범주형 변수를 예측에 활용할 방법 찾기
   - 더 다양한 독립 변수 활용

2. 시계열 분석
   - 정확도 높이기

