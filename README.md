## :exclamation: 프로젝트 소개

##### 안녕하세요 팀 컨트롤(CTRL) 입니다

### :raising_hand: 팀원소개

<table>
  <tr>
      <td align="center"><a href="https://github.com/positivehun/"><img src="https://avatars.githubusercontent.com/u/46879750?v=4" width="100px;" height="120px;" alt=""/><br /><sub><b>김지헌<br>Back-end,팀장</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/abovenormal"><img src="https://avatars.githubusercontent.com/u/51263415?v=4" width="100px;" height="120px;" alt=""/><br /><sub><b>한세환<br>Back-end,<br/>BE-Navigator</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/kky0455"><img src="/uploads/ca1ed84549493590ab9fb259e389de9f/KakaoTalk_20220819_113647399.jpg" width="100px;" height="120px;" alt=""/><br /><sub><b>김광용<br>Back-end</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/choijinhap"><img src="/uploads/04877aa4d879cebd324a7adbdff561cb/증명사진2___40_1__41____40_1__41_.jpg" width="100px;" height="120px;" alt=""/><br /><sub><b>최진합<br>Front-end, <br>FE-Navigator</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/SingTheCode/"><img src="/uploads/8beab5047633a91697f7cde226fb3432/IMG_0655.JPG" width="90px;" height="120px;" alt=""/><br /><sub><b>박재현<br>Front-end</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/YoonJuhye"><img src="/uploads/0da829915185dca0408988f2a110814c/윤주혜19960421증명사진.jpg" width="100px;" height="120px;" alt=""/><br /><sub><b>윤주혜<br>Front-end</b></sub></a><br /></td>

  </tr>
</table>

### 피트윈 서비스 소개

#####

- #### 프로젝트명 : 너와 나의 공유 옷장 FITWEEN

- #### 진행 기간: 2022.07.05 ~ 2022.08.19

- #### 팀명: 컨트롤(CTRL)

- #### 목표: 지역데이터 + 신체데이터를 활용하여 의류공유를 진행할 수 있는 유저를 연결해주는 매칭 시스템

- #### [fitween 진행 내용 (by notion)](https://151958.notion.site/FITWEEN-4a6746ec06ff428ebf2cedb6100b8230)

- #### 서비스 특징

  - ##### 무분별한 피드 공개보다는 회원가입시 사용된 위치/신체데이터를 활용하여 선택적으로 필요한 정보를 제공하여 소비자 경험에 편의성을 제공합니다.

  - ##### 모바일 웹으로 이동하면서 사용이 가능하고, 웹 소켓과 채팅 DB를 활용하여 실시간 채팅 및 채팅내역 불러오기가 가능합니다.

  - ##### Google Oauth로그인을 활용하여 쉽고 간편하게 로그인 및 회원가입이 가능합니다.
- #### 주요 기능

  | 서비스             | 주요 기능                                                                                                                                                                 |
  | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
  | Google Oauth로그인 | 사용자는 Google 아이디를 통해 쉽게 회원가입/로그인이 가능하다 회원가입시 Kakao 위치기반 서비스를 활용하여 지역을 동록할 수 있고, 신체 데이터를 입력하면 회원가입이 완료됩니다. |
  | 피드 시스템        | 사용자의 이용지역 근처에, 사용자의 신체 사이즈가 비슷한 사람들의 피드를 노출해주고, 팔로우, 팔로잉, 메세지 전송 등의 서비스를 이용할 수 있습니다.                                  |
  | 채팅 시스템         | 채팅을 통해 의류 대여 및 구매에 관련된 일정을 의논할 수 있습니다. 채팅서버는 메세지저장, 읽음확인, 알림기능 등을 지원합니다.                                                     |

- #### 상세기능

  - ##### 소셜로그인

    - ##### 구글 소셜 로그인을 제공합니다.
    - ##### 로그인 유저는 메인 피드에 주변 유저의 게시글을 관람하고 피트윈의 서비스를 이용할 수 있습니다.
    - ##### 비 회원 사용자는 구글 로그인을 통해 서비스를 이용할 수 있습니다.

  - ##### 메인페이지

    - ##### 회원가입 페이지

      - ##### 구글로그인 후 추가정보(키, 몸무게, 성별, 발사이즈 등) 입력이 가능합니다.
      - ##### 카카오 API를 활용해 현재 위치정보를 받아올 수 있습니다.

    - ##### 피드페이지

      - ##### 회원가입 시 작성한 정보를 활용하여 주변에 의류를 공유할 수 있는 유저의 피드가 공개됩니다.
      - ##### 게시물을 클릭하여 게시물 상세 정보를 확인할 수 있습니다.
      - ##### 채팅 버튼을 통해 유저와 의류 대여 및 구매에 관련된 이야기를 나눌 수 있습니다.

    - ##### 피드 작성/수정 페이지

      - ##### 공유할 옷의 카테고리, 글 제목, 가격 내용으로 글을 등록할 수 있습니다.
      - ##### 공유할 옷의 카테고리, 글 제목, 가격 내용, 대여가능 여부를 수정 할 수 있습니다.
      
    - ##### 상세 피드 페이지

      - ##### 피드의 자세한 내용을 확인할 수 있습니다.
      - ##### 작성자의 프로필 페이지로 이동할 수 있습니다.
      - ##### 작성자와 채팅을 할 수 있습니다.
      - ##### 자신이 작성한 글은 수정 페이지로 이동할 수 있습니다.
      - ##### 하트를 눌러 찜 목록에서 확인할 수 있습니다.


    - ##### 프로필 페이지
      
      - ##### 해당 사용자의 팔로워 수, 팔로잉 수를 확인할 수 있습니다.
      - ##### 해당 사용자의 게시글 수를 확인할 수 있습니다.
      - ##### 해당 사용자의 게시글 미리보기를 확인할 수 있고 상세페이지로 이동할 수 있습니다.
      - ##### 본인 프로필 페이지에서는 정보수정, 로그아웃, 탈퇴를 진행 할 수 있습니다.
    
    - ##### 내 정보 수정 페이지
    
      - ##### 성별, 생년월일, 별명, 키, 몸무게, 발사이즈를 수정할 수 있습니다.
    
    - ##### 내 동네 수정 페이지
    
      - ##### 살고있는 동네를 수정할 수 있습니다.
    
    - ##### 채팅 목록 페이지
    
      - ##### 채팅을 진행한 유저들의 채팅방 목록와 마지막 채팅 내용 및 읽지 않는 메세지 개수가 표시됩니다.
      - ##### 채팅방이 없다면 진행 중인 채팅이 없다는 메시지가 표시됩니다.
    
    - ##### 채팅 상세 페이지
    
      - ##### 지금까지 진행했던 대화 내용을 불러옵니다.




## :wrench: 기술스택

### Frontend

<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/><img alt="CSS3" src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white"/><img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white">

### Backend

<img alt="Java" src="https://img.shields.io/badge/java-007396.svg?&style=for-the-badge&logo=java&logoColor=white"/> <br />

<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"><img src="https://img.shields.io/badge/SpringCloud-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"><img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white"><br />

<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white"><br />

### DataBase

<img alt="MySQL" src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/> <br />

### Server

<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=Amazon AWS&logoColor=white"> <br />

<img src="https://img.shields.io/badge/Nginx-RED?style=for-the-badge&logo=Nginx&logoColor=white"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"><img src="https://img.shields.io/badge/JENKINS-D24939?style=for-the-badge&logo=jenkins&logoColor=white"> <br />

### **Version Control**

<img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=GitLab&logoColor=white"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">

### **Issue Tracking System**

<img src="https://img.shields.io/badge/Jira Software-0052CC?style=for-the-badge&logo=Jira Software&logoColor=white"> <br />





## 실행방법

직접 실행하기 싫으면 [배포 사이트](https://koo.fiwteen.kro.kr)로 접속!!

#### Frontend

client 폴더 안에서 아래의 명령어를 실행합니다.

```
환경변수 설정 (.env)

REACT_APP_KAKAO_REST_API_KEY=
REACT_APP_GOOGLE_CLIENT_KEY=
REACT_APP_CLIENT_URI=
REACT_APP_API_URI=
REACT_APP_MOCK_API_URI=
REACT_APP_SOCKET_URI=
```

```
패키지 설치
$ npm install
```

```
프로젝트 실행
$ npm run start
```

#### Backend <br/>

##### Spring <br />

backend-java 폴더 안에서 아래의 명령어를 실행합니다.

```
jar 파일 빌드
$ ./gradlew build
```

```
빌드 파일 실행
$ java -jar ssafy-web-project-1.0-SNAPSHOT.jar
```

