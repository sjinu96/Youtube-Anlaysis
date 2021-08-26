# Youtube-Anlaysis
Sentimental Analysis of Comment and Predicting New Subscriber Using Wavenet and ConvGRU models (About Youtube)

This Repo contains only **implementation code**,

so you can see other codes(e.g., DataLoader) for project in here: [AIYTBConsultant](https://github.com/sjinu96/AIYTBConsultant)

### 🤡AI YouTube Consultant
[AIYTBConsultant](https://github.com/iloveslowfood/AIYTBConsultant)

![image](https://user-images.githubusercontent.com/71121461/130931377-c8126092-24e3-4038-a1cc-e98b5d31d5ec.png)



## Sentimental Analysis (Use GRU and LSTM)
* see the ***Sentimental Analysis.ipynb***


![image](https://user-images.githubusercontent.com/71121461/130931929-b6b4bd6e-631c-41ce-843c-09671253e52a.png)

![image](https://user-images.githubusercontent.com/71121461/130932659-4b20a422-9516-4067-bfe3-f0a91dc55fae.png)


![image](https://user-images.githubusercontent.com/71121461/130932244-af5cb52f-0fed-448a-afbf-690af4d2a717.png)


## Dimension Analysis for Verified Sampling
* see the ***Dimension Reduction & Stratified Sampling.ipynb***

![image](https://user-images.githubusercontent.com/71121461/130931765-9e49f0bb-c7aa-4572-8e15-bc466c0c14ae.png)

![image](https://user-images.githubusercontent.com/71121461/130931787-50220c03-fc25-4b91-b06e-2b857490d4ac.png)



## Predict New Subscriber

### Model
* see the directory ***model***

* 모델 4 : Wavenet

![image](https://user-images.githubusercontent.com/71121461/130923095-44d43420-fb92-4345-ad9c-88d35f6a9c3c.png)
* 모델 5 : ConvGRU

![image](https://user-images.githubusercontent.com/71121461/130923134-63224b2a-b4d8-4023-aeac-f47128b5229e.png)

### Evaluate and Predict New Subscriber
* see the ***Evaluate & Predict.ipnyb***

#### Evaluate

![image](https://user-images.githubusercontent.com/71121461/130932482-8847c715-f9c1-40cf-a206-112fa4f89830.png)

![image](https://user-images.githubusercontent.com/71121461/130924128-69fb9cf5-6be6-4fec-8b52-2c545d4baab9.png)


#### Predict

* Wavenet (for predicting 30 days)
![image](https://user-images.githubusercontent.com/71121461/130923410-967d38a7-f8ec-44e8-aa35-435ba956e53b.png)

* convGRU (for predicting 1 day)
![image](https://user-images.githubusercontent.com/71121461/130924269-7851e75b-fddb-42d4-9d9f-3bdd107d7de6.png)

* convGRU (for predicting 90 days)
![image](https://user-images.githubusercontent.com/71121461/130932578-2a0189c7-2703-476c-9bc1-8ba4b636715a.png)

## 🏃‍♂️프로젝트 기간
* 2020.09~2020.12

## 👀디렉토리 구조
```
AIYTBConsultant
├─data                # 데이터가 저장된 폴더
│  ├─raw              # 수집한 raw 데이터가 저장된 폴더
|  └─train_raw.csv    # 학습에 활용되는 데이터
├─etc                 # 노트북 커널, 각종 분석 플롯 등이 저장된 폴더
├─model               # 모델 모듈 저장 폴더
└─preprocessing       # 전처리 모듈 저장 폴더
```
## 👩‍👧‍👦프로젝트 인원
* 프로젝트 참여자: 고지형(본인), 김양기, 박진수, 안나민
* 담당 교수: 김정래
---
* Capstone projects in the department of mathematics, University of Seoul
* Period: September 2020 ~ December 2020
* Advisor: Prof. Jungrae Kim
* Participants: Jihyeong Ko, Yanggi Kim, Jinsu Park, Namin Ahn


