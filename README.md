
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

<img src="https://www.notion.so/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fc82ba3c7-8cae-4fda-9d08-f09124fb046b%2Fc8768836-7b13-41e5-bc03-ede722cdbb61%2FUntitled.png?table=block&id=b2f90252-3b2f-453f-bdbc-fc735a3eaa00&spaceId=c82ba3c7-8cae-4fda-9d08-f09124fb046b&width=2000&userId=c1298d01-226a-4f5d-a00b-6aaaa9f07d2a&cache=v2" />
<img src="https://www.notion.so/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fc82ba3c7-8cae-4fda-9d08-f09124fb046b%2Fbf55ac06-2b35-4208-9b3a-4d5c8d8526f0%2FUntitled.png?table=block&id=79b0347d-5fa3-42a5-a92a-0357ef6a141a&spaceId=c82ba3c7-8cae-4fda-9d08-f09124fb046b&width=2000&userId=c1298d01-226a-4f5d-a00b-6aaaa9f07d2a&cache=v2" />
<img src="https://www.notion.so/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fc82ba3c7-8cae-4fda-9d08-f09124fb046b%2Fa1519187-322c-409b-ab41-a9421ced4b43%2FUntitled.png?table=block&id=30e9803a-8912-43a4-8994-471996c66ece&spaceId=c82ba3c7-8cae-4fda-9d08-f09124fb046b&width=2000&userId=c1298d01-226a-4f5d-a00b-6aaaa9f07d2a&cache=v2" />
<img src="https://www.notion.so/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fc82ba3c7-8cae-4fda-9d08-f09124fb046b%2F7dd6b511-9bee-4e09-b82b-2c2da920f1e4%2FUntitled.png?table=block&id=8c3684cc-dabc-43e3-9a4b-7e5b290f6fc8&spaceId=c82ba3c7-8cae-4fda-9d08-f09124fb046b&width=2000&userId=c1298d01-226a-4f5d-a00b-6aaaa9f07d2a&cache=v2" />

### 💡 힐스테이트 포웰시티 커뮤니티 센터에 배포
<img src="https://www.notion.so/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fc82ba3c7-8cae-4fda-9d08-f09124fb046b%2Fc372f097-291b-44ec-b916-a1346feb3c4e%2F%25EC%258A%25A4%25ED%2581%25AC%25EB%25A6%25B0%25EA%25B3%25A8%25ED%2594%2584_%25ED%2583%2580%25EC%2584%259D%25EC%25A0%259C%25EC%2596%25B4_%25ED%2594%2584%25EB%25A1%259C%25EA%25B7%25B8%25EB%259E%25A8.jpg?table=block&id=3bb7ea91-bef4-4870-a616-2fad48ba82aa&spaceId=c82ba3c7-8cae-4fda-9d08-f09124fb046b&width=2000&userId=c1298d01-226a-4f5d-a00b-6aaaa9f07d2a&cache=v2" />





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
    
