


![image](https://user-images.githubusercontent.com/487999/79708354-29074a80-82fa-11ea-80df-0db3962fb453.png)

# 배달3
-- Microservice Implementation

1. Saga (Pub / Sub)

![image](https://user-images.githubusercontent.com/109713893/219248028-ccace7cb-9671-40ab-b84e-67775a7306b9.png)


2. CQRS

![image](https://user-images.githubusercontent.com/109713893/219248189-a8ea061f-30a7-45b1-b060-eb078962edcc.png)



3. Compensation / Correlation
주문 및 취소 결과 kafka console 로그
![3 Compensation_Correlation](https://user-images.githubusercontent.com/16378278/218912742-57b7ca19-1137-487b-bfab-07ca86a3cca3.PNG)

-- Microservice Orchestration

1. Deploy to EKS Cluster & 2. Gateway Service Router

![image](https://user-images.githubusercontent.com/109713893/219248611-067d4b1b-1e5f-475e-8243-8212fcb21c9f.png)
 
 
 gateway를 통해 주문 성공하는 화면
![1 deploy_cheeck](https://user-images.githubusercontent.com/16378278/218912729-4254145c-3d11-4b11-bbb0-6e276b3f9c2f.PNG)


3.
Autoscale (HPA)
 autoscaling command 입력 및 변경된 내용
![3 autoscaling](https://user-images.githubusercontent.com/16378278/218912740-2ad31080-4dd2-4ca1-a7e8-2361331b3d22.PNG)

 현재 하나의 front pod 확인
![3 pod](https://user-images.githubusercontent.com/16378278/218912749-0645c8ad-8be9-4206-a36b-4fbf9a1a144f.PNG)

 siege 사용 전
![3 hpa](https://user-images.githubusercontent.com/16378278/218912745-2b14120d-cefe-40ec-8ec6-2901b932b108.PNG)

 siege 사용 후
![3 hpa_2](https://user-images.githubusercontent.com/16378278/218912748-3f19e7a4-597b-40db-bec0-52690b6f75dd.PNG)

 pod 갯수 증가 
![3 auto](https://user-images.githubusercontent.com/16378278/218912738-f43497e7-746e-4163-8516-7abe41a0b8df.PNG)


