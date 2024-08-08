# ⏳ 모래시계 플래너 
크래프톤 정글 5기 나만무 프로젝트입니다.

## 팀원소개
- [김회일](https://github.com/KimHoeil): 팀장, 미디어파이프, UI  
- [김민중](https://github.com/MinjungKim5): 프론트엔드, 모래시계 컴포넌트, UI, WebRTC
- [구자건](https://github.com/AruJoy): 프론트엔드: api 통신, 데이터 처리, 컴포넌트 로직 작성, 레이아웃 개선 / 백엔드: 함꼐하기 방, 업적 관련 도메인 api 작성
- [황교준](https://github.com/kyo-hwang):
- [손찬호](https://github.com/PenLoo98):

## 목차
- [프로젝트 개요](#프로젝트-개요)
- [기능 소개](#기능-소개)
- [기술 스택](#기술-스택)
- [아키텍쳐](#아키텍쳐)
- [시연 영상](#시연-영상)
- [개발 기간](#개발-기간)
- [포스터](#포스터)


## 프로젝트 개요
미루는 습관을 개선하고 더나아가 꾸준히 유지하도록 돕고자 만들어진 프로젝트 입니다.

모래시계를 제공하여 집중력 향상과 심리적 안정에 도움을 주고, 사용자의 활동 기록을 분석하여 통계 피드백을 제공합니다. 또한 같은 목표를 가진 사용자와 함께하여 동기부여를 제공합니다.

## 기능 소개
- **모래시계 타이머 + Todolist** : 모래시계 타이머로 빠른 시작을 할 수있고, 할 일과 연동하여 기록을 저장할 수 있습니다.
  - ![카테고리 추가 1](https://github.com/user-attachments/assets/226813cc-908f-4549-9aed-051c548dd0f4)
  - ![카태고리 추가 2](https://github.com/user-attachments/assets/37d6ec03-73ad-4f34-97b1-3cfb055e8dc1)
  - ![할일 추가](https://github.com/user-attachments/assets/732101de-c1c8-47fd-bd9a-acfc627deff8)
  - ![콘솔 todo list](https://github.com/user-attachments/assets/b34574a3-c67b-4d7f-be30-bf1922785f84)
  - ![할일 완료](https://github.com/user-attachments/assets/b4b11ad7-b58e-4fd1-9cf8-685491147e2a)
  - ![모래시계 완료](https://github.com/user-attachments/assets/1bdb0ac9-2074-4f3b-9c0e-3c1517bb256f)

- **같이하기 화상채팅방**: 같은 목표를 가진 사용자와 함께할 수 있는 실시간 화상 채팅방을 생성하고 참여할 수 있습니다.
  - ![함께하기 압장](https://github.com/user-attachments/assets/eb7952af-4e98-4fce-93c5-840c71b3bbde)

- **졸음 및 자리이탈 감지**: 사용자의 졸음 및 자리이탈을 감지하여 모래시계 타이머를 자동으로 일시정지합니다. 졸음 감지시 엽기 아바타를 생성하여 다른 사용자에게 보이도록합니다.
  - ![졸음감지](https://github.com/user-attachments/assets/9eb41135-8ed1-479f-a089-f4cac8b44473)
  
- **활동기록 통계 제공**: 카테고리별 일간/주간/월간 활동시간 통계를 제공하고, 졸음 및 자리이탈 시간을 계산해서 집중도를 제공합니다.
  - ![다이어리 ui](https://github.com/user-attachments/assets/78d52a79-b6b5-4f9b-a9a5-db2f9c12cea9)
  - ![통계1](https://github.com/user-attachments/assets/d1f3f3ea-4681-4fc6-94e4-94e731683815)
  - ![통계 2](https://github.com/user-attachments/assets/8539a2f3-0246-4e60-b554-0ae0de22080c)

- **AI 일지 작성**: 하루동안 한 일의 메모를 토대로 AI가 일지 작성을 보조해줍니다.
  - ![Ai 일지 작성1](https://github.com/user-attachments/assets/8ca422a2-30ff-4e8c-ab4e-22c1235da742)
  - ![Ai 일지작성 2](https://github.com/user-attachments/assets/9f8baf65-a65b-40fc-aaf7-e751a76bc0e4)


- **캘린더 제공**: 캘린더에 간편하게 일정을 등록하면 D-DAY가 빠른순으로 자동 정렬하여 리스트 형식으로 제공합니다.
  - ![일정 등록](https://github.com/user-attachments/assets/e91ecdfe-8f82-4960-85d7-ab0896d78b1a)


## 기술 스택
- [프론트엔드](https://github.com/VVITNESS-ME/HourglassPlannerFront)

  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white"/>

- [백엔드](https://github.com/VVITNESS-ME/HourglassPlannerBack)

  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white"/>

- 데이터베이스

  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/>
- 형상관리

  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/>

## 아키텍쳐
![image](https://github.com/user-attachments/assets/952edb65-e1d9-4d33-a61b-86ff583e85ba)




## 시연 영상
https://www.youtube.com/watch?v=iDxFz58kxjQ

## 개발 기간
2024.06.20 목  ~ 2024.07.25 목 (총 5주)
- 1주차(6.20~6.27): 아이디어 및 기획 토의

- 2주차(6.27~7.4): 키워드 구체화 및 개발 착수

- 3주차(7.4~7.11): MVP 개발, 초기 버전 완성

- 4주차(7.11~7.18): 사용자 인증, 화상채팅 등 부가 기능 개발

- 5주차(7.18~7.25): 폴리싱 및 추가 기능 구현

## 포스터
![image](https://github.com/user-attachments/assets/69e93ecd-e037-4140-8fed-d3cd3ef48f17)




  






<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->


