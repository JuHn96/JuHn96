<div align="center">

# JuHn's Space

`Study` · `Projects` · `Notes` · `Experiments`

</div>

---

## Stack

<div align="center">

### Backend · Web · Data

[![My Skills](https://skillicons.dev/icons?i=java,spring,python,fastapi,django,react,nextjs,ts,js,mysql,postgres)](https://skillicons.dev)

### Cloud · DevOps · Tools

[![My Skills](https://skillicons.dev/icons?i=aws,docker,git,github,linux,vscode,postman,notion)](https://skillicons.dev)

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20Bedrock-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
</p>

---

## Now

<table>
<tr>
<td width="50%" valign="top">

### eGovFrame Study

![Status](https://img.shields.io/badge/STATUS-IN%20PROGRESS-2ea44f?style=flat-square)
![Type](https://img.shields.io/badge/STUDY-PERSONAL-0969da?style=flat-square)

전자정부 표준프레임워크를 단순히 따라 사용하기보다  
**Java → Spring → DB/MyBatis → JSP → eGovFrame** 순으로 기반 원리부터 학습하고 기록하는 공간입니다.

**Focus**

- WSL / Linux 기반 개발환경 구성
- Java · Spring 핵심 원리 학습
- MyBatis · JSP · eGovFrame 구조 이해
- CRUD 구현 및 공공기관 프로젝트 구조 분석
- 학습 과정과 트러블슈팅 문서화

**Stack**  
`Java` `Spring` `MyBatis` `JSP` `Docker` `Linux`

[**Repository →**](https://github.com/JuHn96/egov-study) · [**Notion →**](https://acute-throne-23e.notion.site/3ea8cae706e6802fba9ed97a0102e617)

</td>
<td width="50%" valign="top">

### Wuwa Build Stats

![Status](https://img.shields.io/badge/STATUS-IN%20PROGRESS-2ea44f?style=flat-square)
![Type](https://img.shields.io/badge/PROJECT-PERSONAL-8250df?style=flat-square)

명조 캐릭터 빌드 데이터를 사용자에게 입력받아  
**선택 비율 · 순위 · 기간별 통계**를 제공하기 위해 개발 중인 개인 프로젝트입니다.

**Current Work**

- 서비스 기획 및 전체 구조 설계
- 데이터 수집 · 통계 구조 설계
- Backend / Web / Android 개발
- Docker 기반 개발환경 구성
- 배포 구조 검토 및 확장

**Stack**  
`FastAPI` `SQLAlchemy` `PostgreSQL` `Next.js` `TypeScript` `Kotlin` `Docker`

[**Repository →**](https://github.com/JuHn96/wuwa-build-stats) · [**Notion →**](https://acute-throne-23e.notion.site/3ea8cae706e680a995bfef442c48aac1)

</td>
</tr>
</table>

---

## Team Projects

<table>
<tr>
<td width="50%" valign="top">

### MeetUs
**AI Meeting Summary & To-Do Archive**

`Bootcamp Team Project` · **AWS 중심**  
**Role:** AI Processing / AWS

회의 음성을 분석해 회의 요약과 참여자별 To-Do를 생성하고 관리하는 서비스입니다.  
AWS 서비스를 조합해 처리 파이프라인과 배포 환경을 구성한 프로젝트입니다.

**Contribution**

- AWS Transcribe 기반 STT 처리
- Amazon Bedrock 기반 회의 요약 · To-Do 추출
- SQS Long Polling 기반 비동기 처리
- S3 / ECS Fargate 기반 서비스 구성
- AI Service Docker 컨테이너 구성
- GitHub Actions + OIDC 기반 CI/CD
- ECS Rolling Update 및 Core API 연동

**Stack**  
`Python` `AWS Transcribe` `Amazon Bedrock` `SQS` `S3` `ECS Fargate` `Docker` `GitHub Actions`

[**Repository →**](https://github.com/Project-AWS-AI-Minutes/AI-Minutes)

</td>
<td width="50%" valign="top">

### Fire Detection
**AI CCTV Fire Detection System**

`Bootcamp Team Project` · **AI / YOLO 중심**  
**Role:** Backend / Integration

YOLO 기반 화재 감지 결과를 CCTV 시스템과 연결해  
실시간 이벤트를 관리하도록 구성한 AI CCTV 프로젝트입니다.

**Contribution**

- FastAPI 기반 Backend 구축
- CCTV · 이벤트 관리 API 구현
- YOLO 추론 결과와 Backend 이벤트 처리 로직 연동
- DB 담당자 데이터베이스와 Backend 연동
- Frontend API · 데이터 흐름 연동
- WebSocket 기반 실시간 이벤트 전달
- MJPEG 스트림 및 이벤트 처리 연동
- Docker Compose 기반 실행환경 구성

**Stack**  
`Python` `YOLO` `FastAPI` `MySQL` `WebSocket` `MJPEG` `Docker Compose`

[**Repository →**](https://github.com/fire-detection-ai/JuHn)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### SHS
**Learning Management System**

`Bootcamp Team Project`  
**Role:** Database / Frontend Support

Spring Boot와 React를 이용해 구축한 수험생 대상 학습 관리 시스템입니다.

**Contribution**

- Database 영역을 중심으로 개발
- MySQL 데이터 관리 및 Backend 연동
- Spring Data JPA 기반 데이터 처리
- 프로젝트 후반 Frontend 개발 지원
- 강좌 목록 · 상세 / 공지사항 / 강사 소개 구현
- Header · Footer · Mega Menu 등 공통 UI 보완
- API 연결 및 화면 연동 오류 수정

**Stack**  
`Java` `Spring Boot` `Spring Data JPA` `MySQL` `React` `Vite` `Axios`

[**Repository →**](https://github.com/LMS-SHS/SHS)

</td>
<td width="50%" valign="top">

### Unme MiniHome
**Mini Homepage Web Service**

`Bootcamp Team Project`  
**Role:** Backend

사용자별 미니홈피를 구성하고 관리할 수 있도록 개발한 Spring Boot 기반 웹 서비스입니다.

**Contribution**

- Spring Boot 기반 Backend 개발
- 사용자 도메인 · 서비스 로직 구현
- 회원가입 · 로그인 기능 구현
- 아이디 / 비밀번호 찾기 기능 구현
- Spring Security 기반 인증 · 접근 권한 처리
- Spring Data JPA 기반 DB 연동
- DB / Frontend 담당자와 데이터 및 기능 연동

**Stack**  
`Java` `Spring Boot` `Spring Security` `Spring Data JPA` `MySQL` `Thymeleaf`

[**Repository →**](https://github.com/Unme-miniHome/JuHn_Unme)

</td>
</tr>
</table>

---

## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=JuHn96&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" />

</div>
