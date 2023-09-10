# DistributedLearning

KU D&C Lab Intern(2023.7~ 2023.8)  


### 데이터셋 및 사용 모델
dataset - cifar10  
model - Resnet18 
- computation(진행완료)  
한 epoch에서 발생하는 iteration 계산 속도의 평균을 낸 후 정상 속도의 2배, 5배 정도로 sleep 함수를 사용해 속도를 늦춰
계산 속도가 느려지는 상황을 연출 

- network  
Linux의 tc(Traffic Control)를 사용해 네트워크 패킷이 손실되는 상황 구현 
