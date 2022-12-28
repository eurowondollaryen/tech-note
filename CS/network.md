# 네트워크 내용 정리
## 네트워크 구성
- DMZ: Demilitarized zone, 외부에 공개하기 위한 네트워크
- SOHO: Small Office, Home Office
> SOHO와 대기업의 네트워크 구성은 다름. 지사가 있는 경우 VPN 필요.
## 프로토콜
- Protocol: 원활하게 통신하기 위한 통신 규약
- OSI 7 Layer: ISO(International Organization for Standardization) 에서 정한 통신 모델
## OSI 7 Layer
7. 응용 계층 (Application Layer)
6. 표현 계층 (Presentation Layer)
5. 세션 계층 (Session)
4. 전송 계층 (Transport)
3. 네트워크 계층 (Network)
2. 데이터 링크 계층 (Data link)
1. 물리 계층 (Physical)
> 하위 계층으로 내려가면서 캡슐화(데이터 전송에 필요한 헤더 추가)
> 상위 계층으로 올라가면서 역캡슐화 한다.
## 물리 계층
- 전송매체를 의미. ex) 0/1 정보를 담은 전파를 전기신호로 변환한다. (랜카드)
- 전송매체 - 유선/무선
- 다이렉트 케이블 : 랜선의 하나로, 단방향 통신, 컴퓨터와 스위치를 연결하는 데 사용하는 케이블
- 크로스 케이블 : 랜선의 하나로, 양방향 통신, PC-PC간 통신을 위한 케이블 (중간에 라인이 꼬여있음)
- 리피터 : 신호를 증폭, 복원하는 기능을 가진 네트워크 중계 장비. 요즘은 다른 네트워크 장비의 기능으로 존재해서 없음.
- 허브 : 신호를 증폭, 복원하는 기능. 여러 PC를 서로 연결할 수 있게 해준다.
  - 허브를 통해 데이터를 특정 PC에 보내려면, 전체 대상으로 보내야 한다. (dummy hub)
- 스위치 : 허브의 dummy한 특성에 대한 대책으로 만든 장비, 
- 