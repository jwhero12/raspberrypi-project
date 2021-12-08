# [3학년 B반 무선네트워크 기말고사 라즈베리 프로젝트]

## 참여자 : 박재현, 신우철, 임수민, 한지원
## 작품명 : Iridescent
#### 개발 동기
 좁은 골목길에는 운전자들이 좌우에서 차가 오는지 확인을 하기 위해서 볼록거울이 있는 것을 보실 수 있습니다. 하지만 운전자들은 볼록거울에 의존하지 않고 직접 갈림길에서 좌우를 살피고 운전을 하곤 합니다. 이 볼록거울의 기능을 더 효율적으로 사용할 수 있는 방법을 생각해보았습니다. 고속도로를 다니다보면 멀리서부터 졸음운전 경고메시지등을 알리는 전광판을 볼 수 있습니다.운전자의 입장에서 큰 전광판으로 멀리서부터 정보를 볼 수 있는 것이 더 효율적이라 생각하였고 볼록거울 대신 골목길에서 좌우로 차나 사람이 오는지를 확인하여 전광판으로 미리 알려줄 수 있다면 좋겠다고 생각하여 이 프로젝트를 개발하게 되었습니다.

![KakaoTalk_20211208_222305531](https://user-images.githubusercontent.com/71167256/145215877-5e840776-dd8b-4cbc-8c9d-51e076666e02.jpg)

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

#### 시연 영상 바로가기 링크 ↓
https://youtu.be/gZNo1Hkg96s

#### 시연 사진
![KakaoTalk_20211127_091257964_02](https://user-images.githubusercontent.com/71167256/145215259-dff5780e-2bdf-4b42-aff2-e921b347cae1.jpg)

![KakaoTalk_20211127_091257964_01](https://user-images.githubusercontent.com/71167256/145215277-edb40ccc-e395-4555-a1ae-3742620ace61.jpg)

![exam](https://user-images.githubusercontent.com/71167256/145219646-e0d6f3b6-e0b3-4838-a21b-1c3fdb12133d.gif)


