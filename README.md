# Taxi Pricing Pipeline  

## 목적
우버 운행데이터와 Pyspark을 이용한 가격 예측 파이프라인 개발
Airflow 이용한 workflow 스케쥴링

<img width="823" alt="image" src="https://user-images.githubusercontent.com/79136484/161663194-65162f62-df41-4e3f-af3a-d0c8e69193d6.png">

 
# 알게된 것
* Pyspark 
* Airflow
* Linear Regression
* HyperParameterTuning 

## 더 공부할 것
* Docker
* Kubernetes
* IaC (infrastructure as code) 개발 : 인프라를 코딩으로 하기 
* 분석가가 어떻게 하면 손쉽게 분석할 수 있을까? 에 대한 고민
* Kafka
 
## Repository 구조
```
.
├── preprocess.py           # 우버데이터 전처리
├── train_model.py          # Linear Regression 모델 트레이닝 
├── tune_hyperparameter.py  # 예측 모델 tuning 
├── taxi-price-pipeline.py  # Airflow DAG 작성
└── README.md
 
```


