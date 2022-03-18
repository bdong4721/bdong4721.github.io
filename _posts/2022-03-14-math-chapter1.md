---
layout: single
title:  "수리통계 개념"

categories:
  - 수학

last_modified_at: 2022-03-14T08:06:00-05:00
---

수리통계학 chapter 1
===
이번 학기동안 배운 수리통계학의 기본 및 핵심개념을 정리하는 노트입니다.










* 확률 실험
Random experiement rules:
1. The outcome can't be predicted with certainty. 
2. Every possible outcome can be described prior to performance of the experiement. 
3. This experiment can be repeated under the same conditions.

![set](https://user-images.githubusercontent.com/47611901/158108540-8289313e-1500-40a6-a183-bb14816bfae6.PNG)

세개의 사건들 C1, C2 그리고 C3 가 sample space C에서 정의 된다면,

![캡처](https://user-images.githubusercontent.com/47611901/158108968-5d00f163-69f6-4037-bdff-00b199baf7e1.PNG)


* 확률 세트의 성질

![캡처](https://user-images.githubusercontent.com/47611901/158109730-f304d42c-5f42-406f-9b61-6a8fe6d5aa86.PNG)

![1](https://user-images.githubusercontent.com/47611901/158109739-cd2c4355-6bf3-40a7-9ec8-a6aacfef2840.PNG)

![2](https://user-images.githubusercontent.com/47611901/158109742-a07f969c-e8cb-4ff3-bcdf-d2cbf3097a8c.PNG)

* 본페르니 부등식: 교사건에 대한 확률값의 경계를 알수 있음.

![캡처](https://user-images.githubusercontent.com/47611901/158110590-b074b7bb-c258-419f-8205-48849f8a710f.PNG)

*Counting* 예제

![1](https://user-images.githubusercontent.com/47611901/158111181-20ea1d1c-2920-41a3-8570-e6aafee2ff6e.PNG)

![1](https://user-images.githubusercontent.com/47611901/158111243-f05cde1b-3259-413a-a5c1-ee97880e1c4c.PNG)


모든 이벤트의 결과는 동일한 확률을 가지고 있다(Same probability to occur)


### 조건부 확률과 독립성


![캡처](https://user-images.githubusercontent.com/47611901/158717864-f302a735-abf3-48a2-8d4a-390ba1b5153a.PNG)

![캡처](https://user-images.githubusercontent.com/47611901/158717970-c4ce47be-8f49-4ee0-9a1e-9a597de129f3.PNG)

## 곱셉 공식
![2](https://user-images.githubusercontent.com/47611901/158717984-f58129cc-4872-4cc6-b07a-236e8993337c.PNG)


## 전확률의 공식: 하나의 확률을 sample space를 이루고 있는 여러 disjoint 한 확률들의 부분으로 표현.

![전확률](https://user-images.githubusercontent.com/47611901/158719069-5b6af3f1-40db-4025-bfae-6b55ebb4d3e2.PNG)


## 베이즈 정리: 조건부 확률/ 전확률
베이즈 정리가 내포하고 있는 의미는 과거의 확률을 통해 미래의 확률을 추측.
베이즈 공식은 조건부 확률공식을 전확률의 공식으로 나눈것.

![베이즈](https://user-images.githubusercontent.com/47611901/158720438-fbe4d36b-5564-445b-a76f-2651e08dfbac.PNG)

추가내용은
[데이터사이언스스쿨](https://datascienceschool.net/02%20mathematics/06.06%20%EB%B2%A0%EC%9D%B4%EC%A6%88%20%EC%A0%95%EB%A6%AC.html#:~:text=%EB%B2%A0%EC%9D%B4%EC%A6%88%20%EC%A0%95%EB%A6%AC%EB%8A%94%20%EC%82%AC%EA%B1%B4,%EB%B3%80%ED%99%94%ED%95%98%EB%8A%94%EC%A7%80%EB%A5%BC%20%ED%91%9C%ED%98%84%ED%95%9C%20%EC%A0%95%EB%A6%AC%EB%8B%A4 "베이지안")


베이즈 정리는 사건 B가 발생함으로써(사건 B가 진실이라는 것을 알게 됨으로써, 즉 사건 B의 확률 P(B)=1이라는 것을 알게 됨으로써) 사건 A의 확률이 어떻게 변화하는지를 표현한 정리다. 따라서 베이즈 정리는 새로운 정보가 기존의 추론에 어떻게 영향을 미치는지를 나타낸다.



* 사건 독립의 필요충분조건
![독립 필충](https://user-images.githubusercontent.com/47611901/158721483-8b6e90ce-5fbe-4097-8b38-78031a115d5b.PNG)



* 상호 독립
![상호 독립](https://user-images.githubusercontent.com/47611901/158727495-d526086d-b452-4241-a1e5-27df20cbdfa6.PNG)
![상호 독립2](https://user-images.githubusercontent.com/47611901/158721761-55f8b7d8-1a84-4b98-8156-5002c0c9c25d.PNG)

### 확률 변수
사건의 모든 결과를 나열하기 힘들때 실수를 이용해 변수에 확률을 할당
EX) 동전을 던져서 앞면이 나오는 경우를 1, 뒷면이 나오는 경우를 0으로 하고 X(0), X(1) 같이 표현
동전을 던져서 앞 뒷면이 나올 확률은 각각 1/2 이므로 X(0)=1/2 X(1)=1/2 와 같이 표현 될 수 있음.

![확률변수](https://user-images.githubusercontent.com/47611901/158722181-d8a4e79a-2abb-4bd2-a849-c191000d7aa9.PNG)


### 누적 분포 함수
![누적 분포](https://user-images.githubusercontent.com/47611901/158722259-47507b5e-b942-43f3-ae57-0194ee2f87d5.PNG)

### 누적 분포 함수의 필요충분조건
![누적 분포 필충](https://user-images.githubusercontent.com/47611901/158722820-65a98222-1211-4539-849b-5d3350930d24.PNG)
![필충2](https://user-images.githubusercontent.com/47611901/158722824-2d47d433-fb8b-48b7-94d1-4f890b998d1a.PNG)


* 누적 분포 함수 성질


![캡처](https://user-images.githubusercontent.com/47611901/158725824-2d92a038-194b-4305-8505-4ce012aa3717.PNG)
![캡처](https://user-images.githubusercontent.com/47611901/158725949-337afd29-f510-404c-aec2-6c8376816dc6.PNG)


* 이산 확률 변수와 pmf


![pmf](https://user-images.githubusercontent.com/47611901/158726197-bfd497b5-ec12-4951-bc41-c3ba29291d67.PNG)


* pmf 성질


![pmf 성질](https://user-images.githubusercontent.com/47611901/158726219-5214b4e1-d24d-4f6f-b060-60f36ac6e991.PNG)


* cdf 성질


![cdf](https://user-images.githubusercontent.com/47611901/158726305-8cba8ada-24ed-44fe-ae65-faaae2e4bf8f.PNG)
모든 구간에서 연속이기 때문에 한점에서 왼쪽 극한을 빼면 0이 됨.
![cdf](https://user-images.githubusercontent.com/47611901/158726509-166b37a8-c547-4c8f-bd99-fa336a7a8b68.PNG)


* 연속성에 관한 정의


![pdf 연속성](https://user-images.githubusercontent.com/47611901/158726664-dcaaf1d6-305a-4fb0-8539-76bec67f1f23.PNG)

위 정의에서 pdf를 적분하면 cdf가 됨.







* pdf와 pmf를 따로 떼서 보지 않고 비슷한 성질로 정리


![pmf pdf](https://user-images.githubusercontent.com/47611901/158726895-23be7000-ad54-4bf9-a947-b1ecc1d43f53.PNG)

pmf는 시그마 pdf는 적분으로 표현. 또한 두 함수 모두 양수



* 두 함수가 같은 분포를 가질 조건. 단 값은 다름.

![같은 분포](https://user-images.githubusercontent.com/47611901/158727170-d57e145f-914e-443d-90b6-ed3b9505130e.PNG)
  
  

## 확률 변수 함수의 분포
![확률변수함수 분포](https://user-images.githubusercontent.com/47611901/158729949-56468814-2706-40d4-bee8-72bd50e396dd.PNG)

## 3가지 방법
1. cdf method
2. 적률생성함수
3. transformation

## cdf method (Ex 1.5.10)

![cdf method](https://user-images.githubusercontent.com/47611901/158730193-7ba3f227-48bb-464f-8e1e-d8bc5fbdb5ed.PNG)

![transformation](https://user-images.githubusercontent.com/47611901/158730364-54a2a3ca-fdb5-4000-a59a-ef5261314b23.PNG)
![transformation2](https://user-images.githubusercontent.com/47611901/158730370-616febbd-d0d5-4fc9-a675-a78673c850a6.PNG)
