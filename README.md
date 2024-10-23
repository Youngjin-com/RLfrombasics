# 바닥부터 배우는 강화 학습

<img src="https://www.youngjin.com/images/book_cover/9788931463170.jpg" height="350px" style="border: 2px solid grey;">

[바닥부터 배우는 강화 학습
 (영진닷컴)](https://blog.naver.com/ydot/222044918813)

『바닥부터 배우는 강화 학습』은 강화 학습을 모르는 초보자도 쉽게 이해할 수 있도록 도와주는 입문서다. 현업의 강화 학습 전문가가 직접 설명해 강화 학습에 가장 기본이 되는 개념 설명부터 실무 사례까지 한 권으로 정리했다. 강화 학습의 뼈대가 되는 MDP부터 딥러닝과 강화 학습이 만나는 지점 및 학습 방법론, 알파고, 알파고 제로까지 다룬다. 나아가 유명 게임인 블레이드&소울 비무에 실제로 강화 학습을 적용하며 실무에서 얻은 팁과 노하우를 배워본다.


**저자** 노승은  
**발행일** 2020년 09월 15일  
**크기** 152*225mm   
**쪽수** 304쪽  
**가격** 22,000원  
**ISBN** 9788931463170  

<br>

## 💡Versions (버전)
GYM 라이브러리 버전 0.26.2 이상 에서 테스트 되었습니다.
이보다 낮은 버전의 GYM 라이브러리를 사용하신다면 본 코드가 올바르게 동작되지 않을 것입니다!
Please use latest version of the GYM library. 

<br>

## 💡Typo(오타)
1. 챕터 5 : ch5_mclearning.py 코드 97라인  <br>
(수정 전) cum_reward = cum_reward + gamma * reward <br>
(수정 후) cum_reward = reward + gamma * cum_reward <br>
Thanks to goodjian7

2. 챕터 3 : 67, 69 페이지 OX 퀴즈 <br>
(수정 전) r_t+1 + gamma * r_t+1 + ... <br>
(수정 후) r_t+2 + gamma * r_t+2 + ... <br>
Thanks to namdori61

<br>

## 💡실습용 예제 파일 & 소스 코드
도서 실습에 필요한 예제 파일과 소스 코드는 챕터별로 구성하였으며, 깃허브 저장소뿐만 아니라 [영진닷컴 홈페이지](https://www.youngjin.com/reader/pds/pds.asp)에서도 다운로드받을 수 있습니다.  
코드 작성 시에는 코드를 직접 입력하거나, 책에서 제공하는 소스 코드 파일을 사용하세요.

<br>

## 💡문의 및 정오표
- [문의](mailto:Support@youngjin.com)
- [정오표](https://www.youngjin.com/Artyboard/mboard.asp?strBoardID=errata)
