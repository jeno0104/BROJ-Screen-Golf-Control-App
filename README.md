
# (주) 브로제이에서 진행했던 프로젝트 내용입니다.
💡 회사 내규에 따라 코드는 가져올 수 없었습니다.
아래 내용은 제가 구현한 내용을 정리한 것입니다.
### 팀 구성
Front-end: 2(web 1, app 1)

Back-end: 1

기획&디자인: 1

# 📖 상세 내용


### 💡 스크린 골프를 운영하는 매장에서 실시간으로 타석을 제어할 수 있는 프로그램입니다
해당 앱은 타석에 바로 입장, 예약, 예약 취소, 예약 조회 기능을 제공하고 있습니다.

</aside>

![1](https://github.com/user-attachments/assets/6d120fb6-6e58-4ace-87f6-0ca9a4b7e33f)
![2](https://github.com/user-attachments/assets/536b8838-fbcb-48ad-8380-7e43a20a32c6)
![3](https://github.com/user-attachments/assets/09f43ed8-e987-4ef5-91d3-33e68cfff013)
![4](https://github.com/user-attachments/assets/e9a9bc3d-e4cb-4358-98cf-5095215e4df8)
![5](https://github.com/user-attachments/assets/941ac057-f22a-4322-90e1-4979e7e81382)

### 💡 힐스테이트 포웰시티 커뮤니티 센터에 배포
![6](https://github.com/user-attachments/assets/deb7f0b0-3d8c-4234-bc15-d962a41bf5aa)

- 현재 국내 10곳에 설치 및 해외 베트남 매장과도 계약이 체결되어 12월에 설치 예정

🛠️사용 기술 및 라이브러리

- React-native
- ActiveMQ
- Mobx

# 💻 담당한 기능(React-native App)

- 센터 로그인
    - ex) 에이블짐 1호점, 2호점… 다지점이 있기 때문에 존재하는 기능
- 예약(바로입장)
    - 빈 타석이 있을 시 바로 입장하는 기능
- 대기
    - 이용 중인 타석에 대기를 거는 기능
- 대기 취소
    - 예정된 대기를 취소하고 싶을 때 취소하는 기능
- 대기 조회
    - 대기 내역 조회 기능
    
