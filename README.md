# 김강민

제가 만든 것이 누군가에게 도움이 될 때 가장 뿌듯합니다.

새로운 기술을 써보는 것도 재미있지만, 그 기술로 불편했던 일을 조금 더 편하게 만들었을 때 기억에 오래 남습니다. 보드게임 추천 화면이 너무 느려서 API를 다시 고쳤던 일도, 로봇이 발견한 상황을 관리자가 바로 확인할 수 있도록 서버 기능을 붙였던 일도 그랬습니다.

AI부터 백엔드, 배포까지 이것저것 해왔습니다. 처음 맡은 분야가 아니더라도 프로젝트에 필요하면 배우면서 해결하려고 합니다.

---

## Projects

### 01. [별빛뉴스](https://github.com/kimgm1018/star_news)
**여러 기사에 흩어진 하나의 사건을 연결하는 뉴스 서비스**

<img src="https://raw.githubusercontent.com/kimgm1018/star_news/master/docs/images/readme/presentation-cover.png" alt="별빛뉴스 프로젝트 대표 이미지" width="720" />

같은 사건을 다룬 기사가 여러 개일 때, 기사마다 따로 읽어야 전체 흐름이 보이는 점에서 출발한 프로젝트입니다. 기사에서 사건과 인물, 기관 등의 관계를 추출해 그래프로 연결하고, 그 관계를 따라 뉴스를 볼 수 있도록 만들었습니다.

저는 주로 **인프라와 배포 환경**을 맡았습니다.

- Jenkins를 이용한 CI 환경 구성
- Docker Compose 기반 서비스 실행·배포 환경 구성
- Spring Boot, FastAPI, 데이터베이스가 함께 동작하는 환경 설정
- 브랜치 규칙과 협업 과정 정리

여러 파트에서 만든 코드가 실제 서버에서 하나의 서비스로 돌아가도록 만드는 경험을 했습니다.

**SSAFY 팀 프로젝트 최우수상**

### 02. [R0-Ki](https://github.com/kimgm1018/RoKi)
**반복 순찰을 돕는 자율주행 로봇과 관제 서비스**

로봇이 단지를 순찰하면서 이상 상황을 찾고, 관리자는 관제 화면에서 이를 확인하는 프로젝트입니다.

처음에는 객체 탐지와 OCR을 맡았습니다. 번호판처럼 한 번의 인식만으로는 결과가 불안정한 경우가 있어 여러 프레임의 결과를 비교하고 보완하는 작업을 했습니다.

프로젝트 중간에는 백엔드에도 사람이 필요해 **통계와 AI 파이프라인 관련 API**를 맡았습니다. 탐지 결과를 저장하고 관제 기능에서 사용할 수 있도록 연결하는 작업이었습니다.

4주라는 짧은 기간이었지만 실제 로봇으로 시연까지 마쳤습니다.

**SSAFY 팀 프로젝트 우수상**

### 03. 할래말래
**조건과 취향에 맞는 보드게임을 찾아주는 추천 서비스**

2명이 함께 만든 프로젝트입니다. 데이터 수집부터 KNN 추천 모델, Django API, Vue 화면까지 나눠서 개발했습니다.

기능을 붙인 뒤 화면이 뜨는 데 약 10초가 걸리는 문제가 있었습니다. 프론트엔드만 손보기보다 API가 어떤 데이터를 몇 번 요청하는지부터 확인했고, **응답 구조를 바꾸고 캐싱을 적용해 1초 이내로 줄였습니다.**

추천이 잘되는 것도 중요하지만, 사용자가 결과를 기다리다 나가버리면 의미가 없다는 걸 느낀 프로젝트였습니다.

*팀 저장소는 비공개입니다.*

---

## Other Work

### SPMED — 유전자·약물 데이터 관련 개발

생소한 분야였지만 필요한 내용을 공부하면서 세 가지 작업을 했습니다.

- **유전자 변이 판별:** 알고리즘을 개선해 정확도를 약 98% 수준까지 높였습니다.
- **약물 리포트:** 유전자·약물 정보를 정리해 사람이 읽기 쉬운 리포트로 만드는 기능을 개발했습니다.
- **AI 챗봇:** 관련 자료를 검색해 질문에 답하고, 문의·예약 과정을 돕는 챗봇을 개발했습니다. ([관련 코드](https://github.com/kimgm1018/chat_bot))

### [커뮤니티 텍스트 분석](https://github.com/kimgm1018/G_every_time_clowl)

커뮤니티 게시글 408건과 댓글 7,508개를 수집해 텍스트를 분석하고, 한국어 분류 모델을 적용해 표현 유형을 살펴봤습니다.

### 멘토링

한 학기 동안 Python과 자료구조, 알고리즘 기초를 멘토링했습니다. 제가 아는 내용을 설명하는 것과 상대가 이해할 수 있게 설명하는 것은 다르다는 걸 배웠습니다.

---

## Skills

프로젝트에서 직접 사용해 본 기술 위주로 적었습니다.

- **Backend:** Java, Spring Boot, Python, Django REST Framework, FastAPI
- **AI / Data:** PyTorch, scikit-learn, LangChain, LangGraph, BERT
- **Database / Infra:** MySQL, PostgreSQL, Neo4j, Docker, Jenkins, Nginx
- **Frontend:** Vue.js, React, JavaScript

## These Days

요즘은 Spring Boot로 서버 구조를 더 깊이 공부하고 있습니다. AI Agent가 여러 도구를 호출하고 작업을 나누는 방식, AI 기능을 실제 서비스에서 안정적으로 운영하는 방법에도 관심이 있습니다.

---

## GitHub Stats

![GitHub activity](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kimgm1018&theme=default)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kimgm1018&layout=compact)

---

## Contact

- GitHub: [kimgm1018](https://github.com/kimgm1018)
- Email: kimgm1018@naver.com
