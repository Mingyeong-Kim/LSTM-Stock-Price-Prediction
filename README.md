# LSTM-Stock-Price-Prediction

- **프로젝트 기간: 2020.11(1달, 개인)**
- **프로젝트 개요: LSTM 모델을 활용한 나스닥 주가 예측(데이터 분석)**
- **사용기술: Python(Google Colab), Tensorflow**
- **사용모델: LSTM(Deep Learning)**

## 프로젝트 목표
- 딥러닝 모델을 활용하여 5, 6, 7 거래일 후 나스닥(NASDAQ Composite)지수를 예측하는 모델을 만들고자 했습니다.

## 프로젝트 과정 및 내용

1. 데이터 수집
   - 5년(2015.12.14~ 2020.12.11)동안의 나스닥 종가 데이터
 
2. 모델링
   - 과정
     - 훈련/검증/시험 데이터 분리
     - 정규화
     - LSTM 모델 구현
     - 학습 및 예측

3. 모델 평가 및 분석
   - 모델평가 지표: RMSE


## 프로젝트 결과
- 모델1, 모델2를 구현하여 학습 및 예측을 통해 성능을 비교분석 하였다.
- 모델2의 성능이 가장높았으며 가장 학습이 잘되는 모델로 판단되었다.
 
- **RMSE**
  - <img width="300"  height="200" src="https://user-images.githubusercontent.com/65681568/138142069-5d5a11db-c396-444b-b045-142f645a6ba3.png">
  - **RMSE of train(훈련 데이터 RMSE):** 134.324
  - **RMSE of val(검증 데이터 RMSE):** 178.675

- **예측값과 실제값 비교 그래프**
  - <img width="600"  height="300" src="https://user-images.githubusercontent.com/65681568/138142747-933c3ffa-5fbf-45be-8abb-60111bc6993a.png">
  - 빨간색(red): 모델이 예측한 값

- **고찰**
  - 데이터의 양을 늘리거나 모델의 parameter를 조절을 통한 성능향상 연구가 더 필요할 것으로 보인다. 


