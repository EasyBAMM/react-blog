# [Book] 리액트를 다루는 기술 - blog
### 저자 - 김민준(velopert) 출판 - 길벗

------------

#### 파일구조
* blog-backend(NodeJS - koa)
``` 
  - src
    |- api
    |   |- auth (로그인) 
    |   |- posts (포스트등록)
    |
    |- lib 
    |
    |- models (mongoDB)
```
* blog-frontend(React)
``` 
  - src
    |- components (구성품)
    |   |- auth (로그인) 
    |   |- common (버튼, 헤더 등)
    |   |- post (포스트 등록)
    |   |- posts (포스트 리스트)
    |
    |- containers (이벤트 핸들러)
    |   |- auth 
    |   |- common 
    |   |- post
    |   |- posts
    |   |- write
    |
    |- lib
    |   |- api (api 요청)
    |   |- styles (컬러)
    |
    |- modules (리덕스 비동기 작업관리)
    |   |- auth (로그인, 회원가입)
    |   |- index (루트 리듀서)
    |   |- loading (api 요청상태)
    |   |- post (세부 포스트 읽기)
    |   |- posts (포스트 메인화면)
    |   |- user (로그인 유저)
    |   |- write (포스트 작성)
    |
    |- pages (페이지 렌더링)
        |- LoginPage (로그인 화면)
        |- PostListPage (포스트 메인화면)
        |- PostPage (포스트 세부화면)
        |- RegisterPage (회원가입 화면)
        |- WritePage (포스트 작성화면)
```

#### AWS 주소
http://ec2-3-34-186-5.ap-northeast-2.compute.amazonaws.com:4000/ 지금 
