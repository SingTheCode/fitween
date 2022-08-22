# 포팅 메뉴얼

### 목차

1. [Frontend 기술 스택 및 라이브러리](#frontend-기술-스택-및-라이브러리)
2. [Backend 기술 스택 및 라이브러리](#backend-기술-스택-및-라이브러리)
3. [배포 및 CI/CD 기술스택 및 라이브러리](#배포-및-cicd-기술스택-및-라이브러리)
4. [DB 접속 정보](#db-접속-정보)
5. [빌드 실행 방법](#빌드-실행-방법)
6. [외부 서비스 정보 활용 정보](#외부-서비스-정보-활용-정보)
7. [DB 덤프 파일](#db-덤프-파일)
8. [시연 시나리오](#시연-시나리오)

## Frontend 기술 스택 및 라이브러리

| Stack             | Version | Description         |
| ----------------- | ------- | ------------------- |
| nodeJs            | 16.15.1 |                     |
| React             | 18.2.0  | Client Framework    |
| PWA               |         | Progressive Web App |
| axios             | 0.27.2  |                     |
| lodash            | 4.17.21 |                     |
| mow               | 0.44.2  |                     |
| net               | 1.0.2   |                     |
| react-cookie      | 4.1.1   |                     |
| sass              | 1.53.0  |                     |
| slick-carousel    | 1.8.1   |                     |
| sockjs-client     | 1.6.1   |                     |
| stompjs           | 2.3.3   |                     |
| styled-components | 5.3.5   |                     |
| uuid              | 8.3.2   |                     |

## Backend 기술 스택 및 라이브러리

| Stack                                                      | Version | Description |
| ---------------------------------------------------------- | ------- | ----------- |
| Java                                                       | 1.8     |             |
| Gradle                                                     | 6.7+    | Build Tool  |
| MySQL                                                      | 8.0.30  |             |
| java-jwt                                                   | 3.19.2  |             |
| spring-security                                            | 1.19.1  |             |
| jsonwebtoken jjwt api                                      | 0.11.1  |             |
| JSONParser, JSONObject version                             | 1.1     |             |
| spring boot devtools                                       |         |             |
| spring mysql connector                                     |         |             |
| lombok                                                     | 1.18.24 |             |
| spring boot starter web                                    | 2.4.5   |             |
| session:spring-session-jdbc                                |         |             |
| spring-boot-starter-data-jpa                               |         |             |
| org.webjars:stomp-websocket                                | 2.3.3-1 |             |
| org.springframework.session:spring-session-jdbc            | 2.4.3   |             |
| org.springframework.boot:spring-boot-starter-oauth2-client | 2.4.5   |             |
| org.springframework.boot:spring-boot-starter-security      | 2.4.5   |             |
| org.springframework.boot:spring-boot-starter-websocket     | 2.4.5   |             |
| io.springfox:springfox-boot-starter                        | 3.0.0   |             |
| io.springfox:springfox-swagger-ui                          | 3.0.0   |             |

## 배포 및 CI/CD 기술스택 및 라이브러리

| Stack   | Version   | Description                      |
| ------- | --------- | -------------------------------- |
| Jenkins | 2.346.2   | CI/CD Tool                       |
| Docker  | 20.10.17  |                                  |
| Nginx   | 1.18.0    | Web Server, Reverse Proxy Server |
| Ubuntu  | 20.04 LTS |                                  |

### 프로퍼티가 정의된 파일 목록

backend-java.src.main.resource.application-properties

## 빌드 실행 방법

#### Frontend

client 폴더 안에서 아래의 명령어를 실행한다.

```
패키지 설치
$ npm install
```

```
프로젝트 빌드
$ npm run build
```

#### Backend <br/>

##### Spring <br />

backend-java 폴더 안에서 아래의 명령어를 실행한다.

```
jar 파일 빌드
$ ./gradlew build
```

```
빌드 파일 실행
$ java -jar ssafy-web-project-1.0-SNAPSHOT.jar
```

## 외부 서비스 정보 활용 정보

### Google Oauth

#### 구글 oauth 로그인을 위한 API

API 소스 주소 : https://apis.google.com/js/platform.js?onload=init

## DB 덤프 파일

C104.sql

## 시연 시나리오

### 홈페이지

**FITWEEN의 첫 페이지입니다.**

<img src="/uploads/a5f82733c901443222896fac7bf00054/그림1.png" alt="그림1" width="300px" />

1. About 페이지로 이동합니다.
2. 구글 로그인 페이지로 이동합니다.

### About 페이지

**FITWEEN의 서비스 설명을 볼 수 있습니다.**

 <img src="/uploads/db3ad0feeb095f20dbf19b1a93073867/그림2.png" alt="그림2" width="800px" />

### 구글 로그인 페이지

**구글 계정이 있다면 FITWEEN 구글 계정으로 로그인을 진행할 수 있습니다.**

<img src="/uploads/4f658ac2539273ccd3f7c7eb0ca190e1/그림3.png" alt="그림3" width="300px" />

1. 해당 계정으로 로그인 및 회원가입이 진행됩니다.

### 개인정보 동의 페이지

**FITWEEN 서비스를 진행하면서 필요한 약관 동의를 요청합니다.**

<img src="/uploads/175171ae7ad1e71f8267abea74f0c311/그림4.png" alt="그림4" width="300px" />

1. 약관을 확인하고 체크합니다.
2. 체크가 완료되면 회원가입 페이지로 이동할 수 있습니다.

### 추가정보 입력 페이지 (동네 등록 미포함)

**회원가입에 필요한 추가정보를 입력합니다.**

<img src="/uploads/4b60d4604c2844ac9f6ad802a08e420b/그림5.png" alt="그림5" width="300px" />

1. 성별, 생년월일, 별명, 키, 무게, 발사이즈를 입력합니다.
2. 입력이 끝나면 동네인증 페이지로 넘어갈 수 있습니다.

### 추가정보 입력 페이지 (동네 등록 포함)

**현재 동네를 탐색할 수 있습니다.**

<img src="/uploads/bc9d5d0acc245a6c022aaf7d2fd1ce60/그림6.png" alt="그림6" width="300px" />

1. 현재 위치를 탐색할 수 있습니다.
2. 탐색이 완료되면 회원가입을 완료하고 게시글 목록 페이지로 이동합니다.

### 게시글 목록 페이지

**비슷한 사이즈, 같은 동네에 있는 사람의 게시글을 카테고리 별로 볼 수 있습니다.**

<img src="/uploads/d02759bcdfdf9e21a3501146a47ac0f1/그림9.png" alt="그림9" width="300px" />

1. 카테고리를 선택할 수 있습니다.
2. 게시글을 클릭해 상세 페이지로 이동할 수 있습니다.
3. 게시글에 대한 정보를 볼 수 있습니다.
4. 좋아요를 클릭할 수 있습니다.
5. 게시글 생성페이지로 이동합니다.
6. 현재 게시글 목록 페이지로 이동합니다.
7. 찜 목록 페이지로 이동합니다.
8. 채팅 목록 페이지로 이동합니다.
9. 마이 페이지로 이동합니다.

### 게시글 상세 페이지

**게시글의 상세 내용을 확인할 수 있습니다.**

<img src="/uploads/74d36ccb34b0af670bafc39b91e0fb84/그림8.png" alt="그림8" width="300px" />

1. 게시글을 올린 사용자를 확인할 수 있고, 클릭할 시 해당 사용자의 프로필 페이지로 이동합니다.
2. 대여가능 여부를 확인할 수 있습니다.
3. 게시글의 상세 내용을 확인할 수 있습니다.
4. 좋아요를 클릭할 수 있습니다.
5. 게시글 수정 페이지로 이동합니다.

### 게시글 생성 및 수정 페이지

**게시글을 생성 및 수정할 수 있습니다.**

<img src="/uploads/4380c2211394c67814584e5d66e73dd4/그림7.png" alt="그림7" width="300px" />

1. 제품의 카테고리를 선택합니다.
2. 제품의 상세 내용을 입력합니다.
3. 게시글의 등록 및 수정을 완료합니다.

### 찜 목록 페이지

**내가 찜한 목록들을 확인할 수 있습니다.**

<img src="/uploads/539e5f8efca16f56f5846a241f59a393/그림10.png" alt="그림10" width="300px" />

1. 게시글 상세 페이지로 이동합니다.

### 채팅 목록 페이지

**채팅방 목록을 확인할 수 있습니다.**

<img src="/uploads/bd987d498260da005772b114661f6646/그림11.png" alt="그림11" width="300px" />

1. 채팅 페이지로 이동합니다.

### 채팅 페이지

**타 사용자와 채팅을 진행할 수 있습니다.**

<img src="/uploads/bce22902dc7012d37dd0a40217e9c249/그림12.png" alt="그림12" width="300px" />

1. 채팅 글, 읽음 여부, 보낸 시간을 확인할 수 있습니다.
2. 메시지를 보내 채팅을 진행합니다.

### 마이 페이지

**나에 대한 정보를 확인할 수 있습니다.**

<img src="/uploads/051918a15991c608a555222589464068/그림13.png" alt="그림13" width="300px" />

1. 나의 별명, 프로필 사진, 팔로우, 팔로워, 게시글 수를 확인할 수 있습니다.
2. 나의 게시글 상세페이지로 이동합니다.
3. 회원 정보에 대한 메뉴를 확인할 수 있습니다.

### 마이페이지 모달 메뉴

<img src="/uploads/a26c11613bd8a94d055a8a0a12e77c7a/그림14.png" alt="그림14" width="300px" />

1. 프로필 정보 수정 페이지로 이동합니다.
2. 로그아웃을 진행합니다.
3. 회원 탈퇴를 진행합니다.

### 프로필 수정 페이지 (동네 등록 미포함)

[추가정보 입력 페이지 (동네 등록 미포함)](##추가정보-입력-페이지-동네-등록-미포함)와 동일합니다.

### 프로필 수정 페이지 (동네 등록 포함)

[추가정보 입력 페이지 (동네 등록 포함)](##추가정보-입력-페이지-동네-등록-포함)와 동일합니다.
