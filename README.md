


![image](https://user-images.githubusercontent.com/487999/79708354-29074a80-82fa-11ea-80df-0db3962fb453.png)

# 배달3
## Microservice Implementation

1. Saga (Pub / Sub)

![image](https://user-images.githubusercontent.com/109713893/219248028-ccace7cb-9671-40ab-b84e-67775a7306b9.png)


2. CQRS

![image](https://user-images.githubusercontent.com/109713893/219248189-a8ea061f-30a7-45b1-b060-eb078962edcc.png)



3. Compensation / Correlation
주문 및 취소 결과 kafka console 로그
![3 Compensation_Correlation](https://user-images.githubusercontent.com/16378278/218912742-57b7ca19-1137-487b-bfab-07ca86a3cca3.PNG)

## Microservice Orchestration

1. Deploy to EKS Cluster & 2. Gateway Service Router

![image](https://user-images.githubusercontent.com/109713893/219266912-34cc5c60-738d-43ad-9d96-86fe8658d843.png)


3.
Autoscale (HPA)
- autoscal 설정
![image](https://user-images.githubusercontent.com/109713893/219271057-c9586cbf-5cf6-4d4d-9c7e-47fe9834bc3e.png)

- siege 이용 부하 생성
![image](https://user-images.githubusercontent.com/109713893/219271160-8e53ef8f-5e66-4d4b-952d-a239e7a517f7.png)

- 결과 
![image](https://user-images.githubusercontent.com/109713893/219270941-5e9e0913-784e-43e3-b222-58ef272f7aca.png)
