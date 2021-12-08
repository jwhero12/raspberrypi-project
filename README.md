# [3학년 B반 무선네트워크 기말고사 라즈베리 프로젝트]

## 참여자 : 박재현, 신우철, 임수민, 한지원
## 작품명 : Iridescent
#### 개발 동기
 2011년부터 지금까지 평균 교통사고 사망건수는 210만에 달합니다. 보행 중 사망 건수는 7015명, 이 중 골목길에서 사망한 경우는 3118명으로 사망의 약 44%는골목길에서 발생하였습니다. (삼성교통안전문화 연구소의 경찰청 교통사고 통계자료와 보험사 사고 동영상 분석결과에 따름)
 사람과 대중교통, 자가용 뿐만 아니라 자전거와 킥보드까지 이동수단의 범위가 넓어진 시기에 교통사고 사망률, 특히 치사율이 높은 사람-차 사이의 사고율을 낮추기 위해 주변에서 쉽게 볼 수 있는 볼록거울을 조금 더 발전시키는 방향으로 개발하게 되었습니다.

#### 주요특징
① 도로 볼록거울 양쪽의 초음파센서와 카메라를 설치합니다. 차나 사람이 가까이  오면 초음파센서가 거리를 측정하고 일정 거리 이상 가까워지면 카메라 차인지  사람인지 인식하여 통합센서보드에 알려줍니다.
② 보행자나 운전자가 잘 확인하지 않는 볼록거울에 전광판을 둠으로 써 더 눈에 띄고 안전하게 이동할 수 있습니다.

#### 사용된 부품 : 라즈베리파이4, 아두이노, 통합센서보드, 초음파센서, usb카메라

#### 제작과정
① 초음파센서: 아두이노와 연결하여 작동하도록 하였습니다.
② 통합센서보드: 라즈베리파이와 연결하여 작동하도록 하였습니다.
③ 초음파센서는 아두이노를 이용해 코딩한 다음, 데이터 값을 라즈베리 파이가 읽을   수 있도록 하였습니다.
④ USB 카메라: TensorFlow를 이용하여 사람과 차를 인식하도록 하였습니다.
⑤ 거울 및 자동차, 사람 모형은 도로 시연 영상 구성을 위한 대용입니다.
