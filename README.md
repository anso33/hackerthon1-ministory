# hackerthon1-ministory

## 서비스 간단 소개
### MINISTORY
나만의 게시글을 올릴 수있는 게시글 사이트 만들기

### 기능 소개
- 나만의 페이지에, 나만의 카테고리를 만들어, 나만의 게시글을 작성할 수 있다. 
- 댓글, 좋아요, 스크랩을 할 수 있다.

### 기술 스택
- frontend
  - thymeleaf
  - jquery

- backend
  - Java 11
  - Spring Boot
  - Spring Data JPA


- DB
  - MySQL

### ERD
[ERD](https://www.erdcloud.com/d/smw4qbjMBv8rBbif6)
<img width="1060" alt="image" src="https://github.com/Kernel360/hackerthon1-ministory/assets/68376744/29b3a122-7819-4e05-880d-6d710313c3c4">

### 기능 명세서
[ministory 기능 명세서](https://www.notion.so/cc3b387411d14249af695e9073b93be7?pvs=4)

### 화면 설계
[피그마](https://www.figma.com/file/EbqWx8qFW1O9U5jDJUwkfQ/ministory?type=design&node-id=0-1&mode=design&t=Bbw5lxTm8rB38Uh6-0)

### API 문서
로컬에서 서버 돌리시고
http://localhost:8080/swagger-ui/index.html
로 들어가시면 확인할 수 있습니다. 

### 진행 상황
- 게시물
  - 20%
  - 구현 중
  - thymleaf를 이용해서 프론트에 필요한 부분을 만들었다.
    오픈 소스 에디터를 화면에 담아내기 위해 JQuery를 사
    용하였고 이후 게시물을 DB에 저장하는 작업을 진행해야한다.
- 댓글
  - 댓글 종류에 따른 추가 수정 삭제 기능 구현, Comment
    Controller를 만들어서 html 폼에서 댓글 객체을 받
    아와서 백엔드에 저장하는 것은 확인이 필요하다. 
  - 프론트 구현해야함
- 카테고리
  - 메서드 이름 지정 및 내부 로직 구현 진행 중
- 좋아요, 스크랩
  - 백엔드 50%
  - 프론트 구현해야함
  - 좋아요 등록하기 완성
- 로그인
- 회원가입
- 테스트




| **서비스 메인 페이지** | **내 블로그 메인 페이지** |
|:---:|:---:|
| ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/bb9af6a2-6a68-4330-a580-f6552923eeb4) | ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/7976d3e8-331c-419f-9b94-6c5a3742d2dd) |
| http://localhost:8080/post/mainPage | http://localhost:8080/post/myBlog/1 |
| **마이 페이지** | **회원가입 페이지** |
| ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/8df8866c-cd8d-44ec-befb-514652509ea5) | ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/116396c8-424f-45cf-96cc-fdfaaa79e6e3) |
| http://localhost:8080/api/user/mypage | http://localhost:8080/api/user/signup |
| **포스트 작성 페이지** | **포스트 상세 페이지** |
| ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/b297f514-d224-48f6-8a61-427c606c1be4) | ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/1146f960-4ef3-4a86-8bd0-e04fec542422) |
| http://localhost:8080/post/write | http://localhost:8080/post/view/1 |
| **좋아요 모아보기 페이지** | **스크랩 모아보기 페이지** |
| ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/a00dd16f-d531-48e7-ae78-fbfdc0681f44) | ![image](https://github.com/Kernel360/hackerthon1-ministory/assets/147565215/76260bf3-5d7a-469f-b460-00709e8d4c06) |
| http://localhost:8080/api/like/myLikes | http://localhost:8080/api/scrap/myScraps |
