# SynCode

협업형 웹 기반 개발 환경을 목표로 하는 팀 프로젝트 조직입니다.  
현재는 인증(Auth) 및 공통 UI 기반을 우선 구현하며, 이후 프로젝트 방향에 따라 기능을 확장할 예정입니다.

---

## 프로젝트 개요

SynCode는 웹 환경에서 개발 및 학습 경험을 제공하는 서비스를 목표로 합니다.  
현재는 프론트엔드와 백엔드의 기본 구조를 안정적으로 구축하는 것을 1차 목표로 두고 있습니다.

---

## 저장소

### Frontend
[web-ide-frontend](https://github.com/goorm-syncode/web-ide-frontend)

**Web IDE Frontend**  
Vite + React + JavaScript 기반 프론트엔드 프로젝트입니다.

주요 스택:
- Vite
- React
- JavaScript
- React Router
- Redux Toolkit
- Axios
- CSS
- ESLint
- Prettier

---

### Backend
[web-ide-backend](https://github.com/goorm-syncode/web-ide-backend)

**WebIDE Backend**  
Spring Boot 기반 백엔드 서버입니다.  
현재는 인증(Auth) 및 사용자(User) 도메인을 중심으로 구현 중입니다.

주요 스택:
- Java 21
- Spring Boot 3.5
- Gradle
- MySQL
- Spring Data JPA
- Spring Security
- JWT
- Swagger UI

---

## 현재 진행 범위

### Frontend
- 공통 컴포넌트 구축
- 인증(Auth) 화면 구현
- 공통 레이아웃 및 스타일 규칙 정리

### Backend
- 회원가입 / 로그인
- JWT Access Token 인증
- Refresh Token 재발급
- 로그아웃
- 통일된 예외 처리
- Swagger 문서화

---

## 협업 방식

- `feature/*` 브랜치에서 기능 단위 작업
- `develop` 브랜치로 PR 생성
- 리뷰 후 `develop`에 머지
- 배포 전 `develop -> main` PR 진행

---

## 문서 규칙

프론트엔드 저장소에서는 아래 문서를 기준으로 개발합니다.

- `MVP_SCOPE.md`
- `FEATURE_SPEC.md`
- `UI_RULES.md`
- `.agent/instructions.md`

---

## 향후 확장 가능 영역

현재는 Auth와 공통 기반 구현을 우선하고 있으며, 이후 방향에 따라 아래 영역으로 확장될 수 있습니다.

- Workspace / File Tree
- Chat
- Problem / Submission
- Code Execution / Learning Flow

> 위 기능은 확정되지 않았으며, 팀 논의와 멘토링 결과에 따라 변경될 수 있습니다.
