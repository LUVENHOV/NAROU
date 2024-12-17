
# NAROU 🧳
다른 사람들의 여행 경로를 한눈에 비교하고 싶나요? 🙋‍♀️
<br> 
나만의 여행을 위한 효율적인 루트를 계획하고 실시간으로 공유 해 보세요! ✈

### 목차
1. [프로젝트 기간](#1-프로젝트-기간)
2. [사용한 기술 스택](#2-사용한-기술-스택)
3. [서비스 화면](#3-서비스-화면)
4. [주요 기능 설명](#4-주요-기능-설명)
5. [설계](#5-설계)
6. [팀원 소개](#6-팀원-소개)

----

### 1. 프로젝트 기간
  - 2024.01.08 ~ 2024.02.16 (6주)
---
### 2. 사용한 기술 스택
#### Backend

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-236DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/Spring_data_jpa-6DB33F?style=for-the-badge&logo=SpringSecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-brown?style=for-the-badge&logo=JSON%20web%20tokens)
![Querydsl](https://img.shields.io/badge/Querydsl-purple?style=for-the-badge)
![MySQL](https://img.shields.io/badge/mysql-%2300f?style=for-the-badge&logo=mysql&logoColor=white)

#### FrontEnd
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Node.js](https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000)
![Styled-component](https://img.shields.io/badge/Styled_Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-purple?style=for-the-badge)
![Axios](https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![Material UI](https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white)

---

### 3. 서비스 화면
* 메인페이지
  <table>
    <tr>
      <td>
        <img src="src/img/main.gif" width="100%" />
      </td>
    </tr>
  </table>

* 무한스크롤
  <table>
    <tr>
      <td>
        <img src="src/img/infinite_scroll.gif" width="100%" />
      </td>
    </tr>
  </table>

* 필터링 검색
  <table>
    <tr>
      <td>
        <img src="src/img/search.gif" width="100%" />
      </td>
    </tr>
  </table>

* 게시글 작성
  <table>
    <tr>
      <td>
        <img src="src/img/create.gif" width="100%" />
      </td>
    </tr>
  </table>

* 프로필
  <table>
    <tr>
      <td>
        <img src="src/img/profile.gif" width="100%" />
      </td>
    </tr>
  </table>

* 스크랩
  <table>
    <tr>
      <td>
        <img src="src/img/scrap.gif" width="100%" />
      </td>
    </tr>
  </table>

* 비교
  <table>
    <tr>
      <td>
        <img src="src/img/compare.gif" width="100%" />
      </td>
    </tr>
  </table>

---

### 4. 주요 기능 설명

  - 회원 관리
    - 멤버 회원가입/탈퇴, 중복 아이디 체크, 토큰 활용 인증, 인증코드 확인
    - 유저 닉네임 및 소개 조회/수정, 프로필 사진 등록/수정, 팔로우/팔로잉, 팔로우/팔로잉 목록 확인
    - 스크랩한 게시글 조회

  - 게시글 검색 및 필터 기능
    - 작성자, 제목으로 게시글 검색
    - 최신순, 인기순으로 게시글 정렬
    - 필터 조건을 설정하여 필터 검색
    - 사진 모드와 경로 모드로 게시글 조회
    - 무한스크롤

  - 게시글
    - 좋아요, 스크랩, 댓글
    - 태그 지정, 태그 기반 검색
    - 피드별 장소, 사진 등록(등록 시 Cropper로 줌 인/아웃 가능)
    - 피드 기반 경로 보여주기
    - 썸네일 등록

  - 비교
    - 두 게시글을 가져와 맵 상에서 경로 비교
    - 경로의 상세 정보 확인


---

### 5. 설계

* ERD
  <table>
    <tr>
      <td>
        <img src="src/img/erd.png" width="100%"/>
      </td>
    </tr>
  </table>

* Architecture
  <table>
    <tr>
      <td>
        <img src="src/img/architecture.png" width="100%"/>
      </td>
    </tr>
  </table>

* Figma
  <table>
    <tr>
      <td>
        <img src="src/img/figma.png" width="100%" />
      </td>
    </tr>
  </table>

* FlowChart
  <table>
    <tr>
      <td>
        <img src="src/img/flowchart.png" width="100%"/>
      </td>
    </tr>
  </table>

---

### 6. 팀원 소개
<table width="100%">
<tr>
    <td width="33%" align="center">
      <img src="https://secure.gravatar.com/avatar/741e093face839ab53462105e5451343d82ad13aa97d66e0f90769d6b5a4be3b?s=160&d=identicon" width="100%"/>
      <b><a">손의성</a></b> 
    </td>
    <td width="33%" align="center">
      <img src="https://secure.gravatar.com/avatar/78579195d2baf00be1589712a0b119ce680514beac56179c0944624a0127f2cf?s=160&d=identicon" width="100%"/>
      <b><a">오주현</a></b> 
    </td>
    <td width="33%" align="center">
      <img src="https://avatars.githubusercontent.com/u/92037253?v=4" width="100%"/>
      <b><a href="https://github.com/LUVENHOV">이승연</a></b> 
    </td>
  </tr>
  <tr>
    <td width="33%" align="center">
      서기<br>
      젠킨스 파이프라인 작성<br>
      댓글 기능 구현
    </td>
    <td width="33%" align="center">
      백엔드 팀장<br>
      로그인 기능 구현<br>
      회원 관련 기능
    </td>
    <td width="33%" align="center">
      인프라(CI/CD)  <br>
      게시물 CRUD<br>
      필터링 검색 기능 구현
    </td>
  </tr>
  <tr>
    <td width="33%" align="center">
      <img src="src/img/nyk.jpg" width="100%"/>
      <b><a href="https://github.com/baloo365">나유경</a></b> 
    </td>
    <td width="33%" align="center">
      <img src="src/img/lgh.jpg" width="100%"/>
      <b><a href="https://github.com/goldbutnew">이금현</a></b> 
    </td>
    <td width="33%" align="center">
      <img src="src/img/lwj.png" width="100%"/>
      <b><a href="https://github.com/uuniversey">이우주</a></b> 
    </td>
  </tr>
  <tr>
    <td width="33%" align="center">
      지도 API 관련 로직<br>
      비교 페이지<br>
      게시물 무한 스크롤 구현
    </td>
    <td width="33%" align="center">
      게시글, 코멘트 CRUD<br>
      실시간 채팅 기능<br>
      UI/UX
    </td>
    <td width="33%" align="center">
      팀장<br>
      회원 관련 기능<br>
      검색 및 필터
    </td>
  </tr>
</table>

