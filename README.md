# COVID19 
#### this is a repository for my dissertation : COVID19 CORPUS ANALYSIS

## 코로나19 관련 신문기사의 언어사용 분석
### CORPUS 수집

<img width="375" alt="image" src="https://user-images.githubusercontent.com/96685399/196040112-80f03725-93c4-448a-9417-dc843b60df2d.png">


### 조선일보, 동아일보, 한겨레, 경향신문의 기사 분석 후 비교

#### Topic Modelling -> keyword analysis

<img src="https://user-images.githubusercontent.com/96685399/196039282-e759e899-735f-45bd-b8e1-beae9d8a5ced.png" width="350" height="250"/>


 * 토픽 변화율
 <img src="https://user-images.githubusercontent.com/96685399/196040398-7d9b444f-d50e-4810-a3ae-ba0329093104.png" width="500" height="200"/>
 <img src="https://user-images.githubusercontent.com/96685399/196040367-99ee8de5-3888-48b6-a1f1-048c5189829e.png" width="500" height="200"/>
 <img src="https://user-images.githubusercontent.com/96685399/196040404-ceaafd8a-2382-4318-824c-84aa100ba464.png" width="500" height="200"/>
 <img src="https://user-images.githubusercontent.com/96685399/196040376-ac3c4499-6d79-42a2-b585-f74a082a4358.png"width="500" height="200"/>


#### Sentiment Analysis 
  ##### 토픽모델링 결과에 기반한 주요 토픽별 감성분석
  ##### KO-BERT 학습
   - NSMC 데이터 & 네이버 쇼핑 리뷰 데이터로 훈련된 모델
   - 4개의 신문사를 제외한 코퍼스 데이터 감성분석 (30만개)
   - 모델 성능평가
   <img width="353" alt="image" src="https://user-images.githubusercontent.com/96685399/196040208-f6cd065b-ed3d-4314-b85d-478dcf3efe3a.png">
   <img width="347" alt="image" src="https://user-images.githubusercontent.com/96685399/196040225-d0475cf0-8c81-4460-b897-25f9f753ab8e.png">
   <img width="249" alt="image" src="https://user-images.githubusercontent.com/96685399/196040228-4692dd3f-963a-4d37-b324-0239d1ae1f12.png">
     
  ##### 분석 결과
   1) 전체 기사 (4개의 신문사 감성분석)
  <img width="381" alt="image" src="https://user-images.githubusercontent.com/96685399/196040432-e7734ae8-54b1-4a4d-9370-a7369582138b.png">
  <img width="371" alt="image" src="https://user-images.githubusercontent.com/96685399/196040486-3b9428ce-ce39-4f6b-b465-ecb92939c4dc.png">


   2) 신문사별 - 토픽별 감성분석
   <img width="367" alt="image" src="https://user-images.githubusercontent.com/96685399/196040452-77d2d7e5-901f-4ec0-bb23-98e0cd49d0c2.png">
   <img width="370" alt="image" src="https://user-images.githubusercontent.com/96685399/196040459-d9f76f61-d39e-4fa2-ab41-0bbbf41d06f7.png">
   <img width="373" alt="image" src="https://user-images.githubusercontent.com/96685399/196040466-3f34cf52-405c-4325-8e39-54b6d282291c.png">
   <img width="383" alt="image" src="https://user-images.githubusercontent.com/96685399/196040475-d3d2643b-598a-4298-afd5-65d3a1373c4e.png">
