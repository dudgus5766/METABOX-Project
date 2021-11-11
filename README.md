# Metabox

---

## 🚂 프로젝트 소개
멀티플렉스 영화 서비스 웹사이트 MEGABOX를 모티브로 한 팀 프로젝트입니다.

각 영화에 대한 사용자들의 리뷰 포스트, 사용자가 관람한 영화에 대해서 포스트를 작성해 리뷰를 남기는 서비스를 React.js, Styled-component를 사용해 개발을 진행했습니다.

### 개발기간

- 2021.09.13 - 2021.09.30

### 개발인원

- FrontEnd
  - 이송현, 김동준, 김영현
- BackEnd
  - 주종민, 윤현묵, 송치헌

### 시연영상

[영상 보러가기](https://www.youtube.com/watch?v=PkHOsGvFzec)

## 🛠 적용 기술 및 구현사항

---

### 실행환경

- MacOSX
- Ubuntu
- Conda 4.10.3 version
- Django 3.2.6 version
- MySQL 5.7 version
- mysqlclient 2.0.3 version
- Django-cors-headers 3.7.0 version

### 적용기술

- FrontEnd : HTML, Styled-compnents, javaScript, React
- BackEnd : Python, Django, MySQL

### 협업도구

- Slack
- Git & Github
- Trello
- Postman

### FrontEnd 구현기능

#### 김영현님

- `[Modal]` : JWT 토큰을 이용하고 유효성 검증을 포함하는 회원가입, 로그인 구현 input값의 객체화를 통한 동일 컴포넌트 사용으로 재사용성 증대 / 카카오 API를 이용하여 카카오 소셜 로그인 구현
- `[MoviePostWrite]` : 이미지 파일을 포함한 무비 포스트 작성 구현 (fetch API를 통한 포스트 데이터 추가 및 렌더링), 50자 이내 제한
- `[MoviePost]` : React(CRA, Hook)를 활용해 포스트 페이지 컴포넌트 제작 및 Frontend 구현 / Query String으로 offset을 통해 포스트 페이지네이션 기능 구현
- `[Footer]` 
- Adobe Photoshop을 사용해 사용자 편의성과 디자인적인 부분을 고려한 포스트 페이지 레이아웃 및 UI 리디자인.

## 📃 Reference

---

- 이 프로젝트는 [메가박스](https://www.megabox.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다
- 학습수준의 프로젝트로 만들었기 때문에 이 코드 및 데모영상을 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다
