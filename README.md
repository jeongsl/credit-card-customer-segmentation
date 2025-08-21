# credit-card-customer-segmentation
[2025 DACON 신용카드 고객 세그먼트 분류 AI 경진대회] 신용카드 고객 세그먼트 분류 모델 개발


## 분석 목적
신용카드 고객 세그먼트(Segment) 분류하는 AI 알고리즘을 하기 위함


## 분석 데이터
[DACON 신용카드 고객 세그먼트 분류 AI 경진대회](https://dacon.io/competitions/official/236460/data)

* Segment: A, B, C, D, E
* 871 columns
* 2.400,000 rows (train data)
* 600,000 rows (test data)
  

## 분석 방법
* Python : Soft Voting Ensemble (XGBoost, CatBoost, LightGBM)
* OverSampling, Hyperparameter tuning (Optuna)


## 분석 결과
F1-score : 0.68780
Ranking : 2등 (상위 1%)
