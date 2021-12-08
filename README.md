# [3학년 B반 무선네트워크 기말고사 라즈베리 프로젝트]

## 참여자 : 박재현, 신우철, 임수민, 한지원
## 작품명 : Iridescent
#### 개발 동기
볼록거울이 있는 골목길에서 교통사고가 많이 일어나는데 보통 골목길에는 운전자를 위해 볼록거울이 설치되어있다. 하지만 운전자들은 볼록거울을 보지않고 갈림길에서 직접 좌우를 살피고 운전을 하여 볼록거울의 필요성이 떨어지는 것을 확인할 수 있다.고속도로에서 "졸음운전을 하지마세요"라는 전광판에서 아이디어를 착안해 골목길에 볼록거울대신 전ㄱ광판으로 좌우에서 차나 사람이 오는지 미리 확인하여 멀리서부터 운전자가 확인할 수 있다면 더 효율적일 것이라 생각하여 개발하게 되었다. 

 골목길에 있는 볼록거울은 운전자를 위해 존재함에도 불구하고 , 그런 골목길에서의 교통사고율은 높다.
 그러한 사고율을 통해 운전자들이 볼록거울은 보지않고 갈림길에서 직접 좌우를 살피고 운전을 하여 볼록거울의 필요성이 떨어지는 것을 확인할 수 있다.
이러한 교통 상황과 고속도로에서 "졸음운전을 하지말라"는 전광판에서 아이디어를 착안해 골목길에 볼록거울대신 전광판으로 좌우에서 차나 사람이 오는지 미리 확인하여 멀리서부터 운전자가 확인할 수 있다면 더 효율적일 것이라 생각하여 개발하게되었다.  
#### 주요특징
① 도로 볼록거울 양쪽의 초음파센서와 카메라를 설치합니다. 차나 사람이 가까이  오면 초음파센서가 거리를 측정하고 일정 거리 이상 가까워지면 카메라 차인지  사람인지 인식하여 통합센서보드에 알려줍니다.   
② 보행자나 운전자가 잘 확인하지 않는 볼록거울에 전광판을 둠으로 써 더 눈에 띄고 안전하게 이동할 수 있습니다.   

#### 사용된 부품
라즈베리파이4, 아두이노, 통합센서보드, 초음파센서, usb카메라

#### 제작과정
① 초음파센서: 아두이노와 연결하여 작동하도록 하였습니다.   
② 통합센서보드: 라즈베리파이와 연결하여 작동하도록 하였습니다.   
③ 초음파센서는 아두이노를 이용해 코딩한 다음, 데이터 값을 라즈베리 파이가 읽을   수 있도록 하였습니다.   
④ USB 카메라: TensorFlow를 이용하여 사람과 차를 인식하도록 하였습니다.   
⑤ 거울 및 자동차, 사람 모형은 도로 시연 영상 구성을 위한 대용입니다.   

### 시연 사진
![KakaoTalk_20211127_091257964_02](https://user-images.githubusercontent.com/71167256/145215259-dff5780e-2bdf-4b42-aff2-e921b347cae1.jpg
![KakaoTalk_20211127_091257964_01](https://user-images.githubusercontent.com/71167256/145215277-edb40ccc-e395-4555-a1ae-3742620ace61.jpg)
)
