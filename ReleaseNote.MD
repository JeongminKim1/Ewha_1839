# 1839_growth
---------------------------------------------------------
--------------------------------------------------------
## Quick Start Guide https://github.com/parkjimin00-a11y/1839_growth/blob/main/ReleaseNote.MD#quick-start-guide


## 전처리와 데이터 로드, 전처리, 학습 등이 모두 담긴 코드 https://github.com/parkjimin00-a11y/1839_growth/blob/main/3-LSTM/mbti_LSTM.ipynb

## 학부 논문_딥러닝 기반 MBTI 성격 유형 분류 연구 https://github.com/parkjimin00-a11y/1839_growth/blob/main/%EB%94%A5%EB%9F%AC%EB%8B%9D%20%EA%B8%B0%EB%B0%98%20MBTI%20%EC%84%B1%EA%B2%A9%20%EC%9C%A0%ED%98%95%20%EB%B6%84%EB%A5%98%20%EC%97%B0%EA%B5%AC.pdf

## 시연 영상_딥러닝 기반 MBTI 성격 유형 분류 연구 https://youtu.be/YJsb7r6x9dM

-------------------------------------------------

-------------------------------------------------

-------------------------------------------------

-------------------------------------------------


# Quick Start Guide


### (1) 
먼저 구글에 로그인 해준다. 

그리고 아래의 코랩 링크에 들어간다. (아래 링크의 코드는 이 레프로터지의 3-LSTM 폴더의 mbti_LSTM.ipynb와 동일하다.)

https://colab.research.google.com/github/parkjimin00-a11y/1839_growth/blob/main/3-LSTM/mbti_LSTM.ipynb

### (2)
링크에 접속했다면 페이지 상단 메뉴의 '런타임>모두실행'을 통해 코랩코드를 실행한다.

![image](https://user-images.githubusercontent.com/90343909/172838896-f73cab15-cace-471b-aabe-7e814f40456b.png)


아래와 같이 '경고: 이 노트는 Google에서 작성하지 않았습니다.' 라는 팝업창이 뜨면 '무시하고 계속하기'를 선택한다.

![image](https://user-images.githubusercontent.com/90343909/172838273-63ceb803-906b-4fcb-8abf-3d59d7f75a45.png)

### (3) 
필요한 패키지가 import 되고, 데이터가 load 된 후(이 데이터는 이 레프로터지의 3-LSTM의 폴더에 있는 데이터와 동일하다.) 

전처리와 4가지 지표의 이진 분류에 대한 학습이 진행되는 것을 확인할 수 있다.

그리고 마지막 부분에는 직접 텍스트를 받아 MBTI 성격 유형을 분류하는 것도 가능한 것을 확인할 수 있다.

### (4)
직접 텍스트를 넣어 MBTI를 분류하길 원한다면
   
   끝에서 2번째에 있는 셀에서 text 변수에 분류하길 원하는 텍스트를 넣고 셀을 실행해 준다.

![image](https://user-images.githubusercontent.com/90343909/172704181-3031e1ff-9f8c-448c-a495-b387a6637988.png)



### (5) 
마지막 셀을 실행해 준다. (text 변수를 input으로 넣은 코드)

![image](https://user-images.githubusercontent.com/90343909/172704350-206fb1eb-4085-4ea4-9362-cd85fb9990a1.png)




### (6) 
그러면 그 텍스트에서 드러나는 MBTI를 예측하는 것을 볼 수 있다.

![image](https://user-images.githubusercontent.com/90343909/172704489-aca5aa55-ef04-4af2-8a26-9d44e87fc1d7.png)

----------------
### (7) 이 프로젝트의 산출물인 논문
#### 학부 논문_딥러닝 기반 MBTI 성격 유형 분류 연구 https://github.com/parkjimin00-a11y/1839_growth/blob/main/%EB%94%A5%EB%9F%AC%EB%8B%9D%20%EA%B8%B0%EB%B0%98%20MBTI%20%EC%84%B1%EA%B2%A9%20%EC%9C%A0%ED%98%95%20%EB%B6%84%EB%A5%98%20%EC%97%B0%EA%B5%AC.pdf

### (8) 이 프로젝트에 대한 설명을 포함한 시연 영상
#### 시연 영상_딥러닝 기반 MBTI 성격 유형 분류 연구 https://youtu.be/YJsb7r6x9dM


### 혹시 위의 Quick Start Guide의 방법으로 했을 때 문제가 있다면 아래의 url로 이동한다. 

https://github.com/parkjimin00-a11y/1839_growth/blob/main/ReleaseNote.MD#other-method

------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------------------------



# Other method

혹시 Quick Start Guide의 방법으로 했을 때 문제가 있다면 직접 소스 코드 파일을 다운받아 구글 드라이브에 업로드 해 코랩으로 파일을 돌리는 방법이 있다.

그 방법은 아래와 같다.

### (1) 
아래 zip파일을 다운 받고 압축을 푼다. 아래 zip파일에 담긴 파일은 코드 파일이다 (이 레프로터지의 3-LSTM 폴더의 mbti_LSTM.ipynb와 동일하다.)

[mbti_LSTM.zip](https://github.com/parkjimin00-a11y/1839_growth/files/8876084/mbti_LSTM.zip)



### (2) 
압축을 푼 폴더 안의 mbti_LSTM.ipynb(코드 파일)을 구글 드라이브에 저장해준다.

### (3) 
위의 (2)에서 구글 드라이브에서 저장한 mbti_LSTM.ipynb(코드 파일)를 열면 코랩으로 코드 파일이 열린다.

### (2)
코랩 페이지 상단 메뉴의 '런타임>모두실행'을 통해 코랩코드를 실행한다.

![image](https://user-images.githubusercontent.com/90343909/172838896-f73cab15-cace-471b-aabe-7e814f40456b.png)

### (3) 
필요한 패키지가 import 되고, 데이터가 load 된 후(이 데이터는 이 레프로터지의 3-LSTM의 폴더에 있는 데이터와 동일하다.) 

전처리와 4가지 지표의 이진 분류에 대한 학습이 진행되는 것을 확인할 수 있다.

그리고 마지막 부분에는 직접 텍스트를 받아 MBTI 성격 유형을 분류하는 것도 가능한 것을 확인할 수 있다.

### (4) 
직접 텍스트를 넣어 MBTI를 분류하길 원한다면, 
   
   끝에서 2번째에 있는 셀에서 text 변수에 분류하길 원하는 텍스트를 넣고 셀을 실행해 준다.

![image](https://user-images.githubusercontent.com/90343909/172704181-3031e1ff-9f8c-448c-a495-b387a6637988.png)



### (5) 
마지막 셀을 실행해 준다. (text 변수를 input으로 넣은 코드)

![image](https://user-images.githubusercontent.com/90343909/172704350-206fb1eb-4085-4ea4-9362-cd85fb9990a1.png)




### (6) 
그러면 그 텍스트에서 드러나는 MBTI를 예측하는 것을 볼 수 있다.

![image](https://user-images.githubusercontent.com/90343909/172704489-aca5aa55-ef04-4af2-8a26-9d44e87fc1d7.png)

----------------
### (7) 이 프로젝트의 산출물인 논문
#### 학부 논문_딥러닝 기반 MBTI 성격 유형 분류 연구 https://github.com/parkjimin00-a11y/1839_growth/blob/main/%EB%94%A5%EB%9F%AC%EB%8B%9D%20%EA%B8%B0%EB%B0%98%20MBTI%20%EC%84%B1%EA%B2%A9%20%EC%9C%A0%ED%98%95%20%EB%B6%84%EB%A5%98%20%EC%97%B0%EA%B5%AC.pdf

### (8) 이 프로젝트에 대한 설명을 포함한 시연 영상
#### 시연 영상_딥러닝 기반 MBTI 성격 유형 분류 연구 https://youtu.be/YJsb7r6x9dM


--------------------------------------------------------
---------------------------------------------------------

## Quick Start Guide https://github.com/parkjimin00-a11y/1839_growth/blob/main/ReleaseNote.MD#quick-start-guide
