# Introduction

#### 2020년 제 14회 공개 SW 개발자 대회 참여 프로젝트 
<https://www.oss.kr/dev_competition>

#### 손글씨 교정 웹사이트(Hand-Writing Correction Website)
<https://github.com/jiminAn/hand_writing_correction_website>

<br/>

# Role

|     팀원     |                       역할                        |          책임                        |
| :---------: | :----------------------------------------------: | :---------------------------------: |
|     [daehoon12(강대훈)](https://github.com/daehoon12)  |     PM &#128081;, 서브 코더     |   프로젝트와 관련된 모든 활동 담당 및 관리, 데이터 추출 및 저장 관련 코더 |
|  [jiminAn(안지민)](https://github.com/jiminAn)   | 메인 코더 |  AI 개발의 메인 코더   |
|     [Rudy-009(이승준)](https://github.com/Rudy-009)   | 테스트 담당자, 서브 코더  | AI 프로그램 개발의 서브 코더 및 테스트 실행 및 관리   |
|    [limjustin(임재영)](https://github.com/limjustin)  |     웹 디자인 및 설계          | UI 설계, 서버 설계 및 관리         |
| [sunjungAn(안선정)](https://github.com/sunjungAn) |         데이터 관리자, 서브 코더          |  프로젝트에 필요한 데이터 수집 및 관리, 데이터 추출 및 저장 관련 코더 |


<br/>

# Website

#### **Initial Page**

![web1](https://user-images.githubusercontent.com/55044278/92071667-4ab92800-edea-11ea-9a84-1e85bbe9a5e5.png)

<br/>

#### **Main Page**

![web2](https://user-images.githubusercontent.com/55044278/92071672-50af0900-edea-11ea-901b-99cc663cdf00.png) 

- 사용자는 캔버스 위에 자신의 손글씨를 작성

![web3](https://user-images.githubusercontent.com/55044278/92071680-5573bd00-edea-11ea-8771-2e200cc7b6ca.png)

- 손글씨를 작성한 후, Download 버튼을 누르고 원하는 글씨체를 선택

![downloadfile](https://user-images.githubusercontent.com/55044278/92071721-72a88b80-edea-11ea-9636-08e414fe5c9a.png)

- 사용자는 자신이 쓴 손글씨를 직접 다운로드 가능

<br/>

#### Practice Page

![web4](https://user-images.githubusercontent.com/55044278/92071684-5a387100-edea-11ea-95c4-6efa081fc7ab.png)

- 사용자가 선택한 글씨체 중 하나를 골라서 오른쪽 캔버스에 가이드 글씨로 표시

![web5](https://user-images.githubusercontent.com/55044278/92071694-5f95bb80-edea-11ea-87b5-4a30f8f7ec52.png)

- 색깔, 굵기를 조절하여 직접 가이드 글씨 위에 손글씨 작성 가능

![resultweb](https://user-images.githubusercontent.com/55044278/92071705-66243300-edea-11ea-9a02-34d57c1c2fa7.png)

- 사용자가 작성한 손글씨 직접 다운로드 가능

<br/>

# Website Demo Video
: 아래 사진을 클릭하면 유트브에서 시연영상을 확인할 수 있습니다  
[![시연영상](https://img.youtube.com/vi/L7WMfmS953A/0.jpg)](https://www.youtube.com/watch?v=L7WMfmS953A)

# Documentation

**문서 정리**

- [daehoon12(강대훈)](https://github.com/daehoon12)
- [jiminAn(안지민)](https://github.com/jiminAn)

------------------------------------
20200810 글자 추출 코드 작성 (Ver 1.0) , 강대훈    
20200814 글자 유사도 비교 코드 작성(Ver 1.0), 안지민&이승준  
20200816 로컬이미지로 학습 데이터 셋 만들기(Ver 1.0), 안지민  
20200817 폰트별 알파벳 이미지 추출 (Ver 1.0), 강대훈  
20200818 폰트별 알파벳 이미지 추출 (Ver 1.1, 소문자 추출 추가) , 강대훈  
20200818 생성된 데이터 셋으로 훈련하기(Ver 1.0), 안지민    
20200818 생성된 모델로 테스트하기(Ver 1.0), 안지민    
20200822 생성된 모델로 테스트하기(Ver 1.1, Dataization 반환값 수정), 안지민  
20200823 과적합 진단을 위한 모델 학습과정 그래프그리기(Ver 1.0), 안지민   
20200825 정확도 문제로 인해 기존 데이터를 EMNIST 데이터로 변경, 강대훈  
20200826 mnist(숫자),emnist(알파벳) 데이터를 이용한 cnn 코드 (Ver 1.0), 안지민   
20200826 훈련된 모델을 로드하여 그림판으로 입력값을 넣어 숫자,알파벳 예측 (Ver 1.0), 안지민  
20200827 연속된 알파벳을 크롭하여 문자 하나하나 분리하는 코드(Ver 1.0), 안선정  
20200827 크롭한 문자 수만큼 모델은 로드하여 알파벳을 예측하는 코드(Ver 1.0), 안선정    
20200829 emnist(알파벳) 데이터를 이용한 cnn 코드 에포크 10->100, 성능 93->98% 증가 (Ver 1.1), 안지민    
20200902 웹사이트 최종본 완성 (Ver 1.1), 강대훈&안지민&이승준&안선정&임재영
