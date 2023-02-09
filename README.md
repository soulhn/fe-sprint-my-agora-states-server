# fe-sprint-my-agora-states-server

## Bare Minimum Requirement Self Checklist

스스로 구현 완료한 부분까지 체크하여 제출합니다.

**my-agora-states-server**

- [ ] `my-agora-states-server/app.js`
  - [x] 모든 Origin, 경로에 대해 CORS 요청을 허용하게 미들웨어를 적용합니다.
  - [x] POST 요청 등에 포함된 body(payload)를 구조화하기 위한 미들웨어를 적용합니다.
  - [x] 서버 상태 확인을 위해 `/` 에서 상태 코드 200으로 응답합니다.
  - [x] `discussionsRouter` 를 이용하여 `/discussions` 경로로 라우팅합니다.
- [x] `my-agora-states-server/router/discussions.js`
  - [x] `GET /discussions`
  - [x] `GET /discussions/:id`
- [x] `my-agora-states-server/controller/index.js`
  - [x] `discussionsController.findAll`
  - [x] `discussionsController.findById`

**my-agora-states-server 과제 제출 (Pull request)**

- [ ] Pull request로 과제 제출

**my-agora-states-server 시작**

- [ ] `package.json` 을 참고하여 나만의 아고라 스테이츠 서버를 로컬 환경에서 실행합니다.

**my-agora-states와 연동하기**

- [ ] my-agora-states-server가 켜져있는지 확인합니다.
- [ ] 로컬 환경에서 실행한 나만의 아고라 스테이츠 서버에서 discussions 데이터를 조회합니다.

## Optional Checklist

스스로 구현 완료한 부분까지 체크하여 제출합니다.

1. **my-agora-states-in-react**
   - [ ] create-react-app으로 프로젝트 생성
   - [ ] 기존에 만든 나만의 아고라 스테이츠를 React로 옮기기
     - [ ] 디스커션 나열 기능
   - [ ] 로컬 환경에서 실행한 나만의 아고라 스테이츠 서버에서 discussions 데이터를 조회합니다.
