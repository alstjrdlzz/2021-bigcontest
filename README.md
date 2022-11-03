# 2021 빅콘테스트 코드


## 코드 ipynb
#### 00.Setting.ipynb
##### :data 폴더(생성 데이터 저장 경로)생성
#### 01.TGS_BARREL_FINAL.ipynb
##### :본팀에서 정의한 배럴 타구와 배럴 타구를 기반으로 하는 파생변수를 만들고, 생성된 데이터를 data 폴더에 저장
#### 02.Feature Engineering.ipynb
##### :이상치처리, 추가적인 파생변수 생성 및 결측값처리, 시각화 등의 Feature Engineering 과정을 거친 후 데이터를 분할하여 data 폴더에 저장
#### 03.Benchmark.ipynb
##### :data 폴더에서 데이터를 불러와서 모델의 성능 비교를 위한 벤치마크 결과 출력
#### 04.Crawling and Modeling.ipynb
##### :data 폴더에서 데이터를 불러와서 본 팀이 구축한 예측 모델을 구현하고 성능을 평가
#### 05.SHAP를 이용한 모델 결과 해석.ipynb
##### :data 폴더에서 데이터를 불러와서 챔피언 모델의 파라미터로 Fitting하고 변수중요도 출력
#### KBO_BARREL_FINAL.ipynb
##### :기존의 KBO 배럴 기준을 적용했을 때의 결과 (01. TGS_BARREL_FINAL.ipynb에서 본 팀이 정의한 배럴 타###  구와의 성능 비교를 위한 코드)
