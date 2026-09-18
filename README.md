<div align="center">

# 남동현 | Software Engineer

### 상태와 데이터의 흐름을 이해하고, 구현과 검증으로 설계를 완성합니다.

AI를 활용해 학습을 가속하되, 제안된 코드를 그대로 받아들이지 않고<br />
선택한 이유와 실제 동작을 직접 설명하고 검증합니다.

[![Blog](https://img.shields.io/badge/Tech_Blog-FF5A4A?style=flat-square&logo=tistory&logoColor=white)](https://app2.tistory.com/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ehdgus5178@gmail.com)

</div>

## About Me

- 사용자 화면부터 API, 데이터 저장, 실시간 동기화까지 이어지는 전체 흐름을 설계하고 구현합니다.
- 문제가 생기면 실제 데이터 흐름을 따라가며 질문을 잘게 나누고, 이해한 내용을 제 언어로 다시 설명합니다.
- AI 기능도 단순 호출에 그치지 않고 판단, 도구 선택, 결과 평가, 재시도와 폴백의 실행 구조로 다룹니다.
- 구현 결과는 테스트와 수치로 검증하고, 팀이 같은 구조를 이해할 수 있도록 이유와 흐름을 공유합니다.

## Core Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

## Featured Project

### [PILO — AI 회의록 기반 실시간 협업 플랫폼](https://github.com/Developer-EJ/PILO)

> 2026.06.19–07.25 · 5인 팀 · 홈 대시보드와 Canvas 설계·구현

TypeScript, Next.js, NestJS, PostgreSQL, Socket.IO, tldraw

- tldraw의 Shape 생성·수정·삭제를 사용자, 세션, Canvas 문맥을 포함한 이벤트로 변환하고 Socket.IO로 동기화했습니다.
- 실시간 화면, Activity Log, Checkpoint, Canvas AI가 같은 상태 변경 경로를 재사용하도록 구조를 통합했습니다.
- Viewport 기반 지연 로딩으로 307개 객체의 초기 로드를 **307개 → 7개(97.7% 감소)**로 줄였습니다.
- 전체 스냅샷 대신 변경 객체만 저장해 대표 단일 Shape 저장량을 **165KB → 452B(99.7% 감소)**로 줄였습니다.
- PILO AI가 작업을 조율하고 Canvas AI가 의도 분류, Shape 검색, 선택 영역 생성을 독립 수행하도록 도메인 멀티 에이전트 구조를 설계했습니다.

[실시간 협업 엔진 설계](https://app2.tistory.com/entry/%ED%81%AC%EB%9E%98%ED%94%84%ED%86%A4-%EC%A0%95%EA%B8%80-%EB%82%98%EB%A7%8C%EB%AC%B4-PILO-tldraw-%EC%9C%84%EC%97%90-%EC%8B%A4%EC%8B%9C%EA%B0%84-%ED%98%91%EC%97%85-Canvas-%EC%97%94%EC%A7%84%EC%9D%84-%EC%A7%81%EC%A0%91-%EC%84%A4%EA%B3%84%ED%95%9C-%EA%B3%BC%EC%A0%95)
· [Viewport·Checkpoint 최적화](https://app2.tistory.com/entry/%ED%81%AC%EB%9E%98%ED%94%84%ED%86%A4-%EC%A0%95%EA%B8%80-%EB%82%98%EB%A7%8C%EB%AC%B4-PILO-Canvas-%EC%A0%84%EC%B2%B4-%EB%8F%99%EA%B8%B0%ED%99%94%EB%A5%BC-Viewport%EC%99%80-%EB%B3%80%EA%B2%BD%EB%B6%84-%EC%A4%91%EC%8B%AC%EC%9C%BC%EB%A1%9C-%EB%B0%94%EA%BE%B8%EA%B8%B0%EA%B9%8C%EC%A7%80)
· [멀티 에이전트 분리](https://app2.tistory.com/entry/%ED%81%AC%EB%9E%98%ED%94%84%ED%86%A4-%EC%A0%95%EA%B8%80-%EB%82%98%EB%A7%8C%EB%AC%B4-PILO-PILO-AI%EC%99%80-Canvas-AI%EB%A5%BC-%EB%8F%84%EB%A9%94%EC%9D%B8-%EB%A9%80%ED%8B%B0-%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8%EB%A1%9C-%EB%B6%84%EB%A6%AC%ED%95%9C-%EC%9D%B4%EC%9C%A0)

## Projects & Learning

### [Player Support Desk](https://github.com/ndh5178/player-support-desk)

Vue 3를 학습하며 만든 게임 고객 문의 운영 도구입니다.

- URL Query, Pinia, Props/Emit의 책임을 나눠 검색·필터·정렬·페이지 상태 흐름을 설계했습니다.
- 350ms debounce, 이전 요청 취소, 요청 ID 검증으로 늦게 도착한 응답이 최신 목록을 덮어쓰지 않도록 했습니다.
- 목록·상세·새로고침 복원·요청 경쟁·오류 복구를 포함한 **37개 테스트**와 타입 검사, 린트, 프로덕션 빌드를 통과했습니다.

[개발 과정](https://app2.tistory.com/entry/Vue%EB%A5%BC-%EC%B2%98%EC%9D%8C-%EB%B0%B0%EC%9A%B0%EB%A9%B0-%EA%B2%8C%EC%9E%84-%EA%B3%A0%EA%B0%9D-%EB%AC%B8%EC%9D%98-%EC%9A%B4%EC%98%81-%EB%8F%84%EA%B5%AC%EB%A5%BC-%EB%A7%8C%EB%93%A0-%EA%B3%BC%EC%A0%95)

### [AI Board](https://github.com/ndh5178/ai-board)

같은 서비스를 Next.js 풀스택과 React·NestJS 분리 구조로 구현하며 AI Agent의 실행 경계를 비교했습니다.

- 채용 공고 입력에서 태그 추출, 외부 검색, 결과 평가, 최대 5회 재시도, 임베딩·ChromaDB RAG 폴백으로 이어지는 추천 Agent를 구현했습니다.
- 원본 데이터는 MariaDB·Prisma, 벡터 데이터는 ChromaDB로 분리하고 MCP Tool과 Agent가 공통 검색 서비스를 재사용하도록 구성했습니다.

[설계와 회고](https://app2.tistory.com/entry/%ED%81%AC%EB%9E%98%ED%94%84%ED%86%A4-%EC%A0%95%EA%B8%80-1516%EC%A3%BC%EC%B0%A8-%ED%9A%8C%EA%B3%A0%EB%A1%9D-%EB%84%A4-%EA%B0%80%EC%A7%80-%EB%B0%B1%EC%97%94%EB%93%9C%EB%A5%BC-%ED%95%B4%EB%B3%B4%EB%A0%A4%EB%8B%A4-%EB%91%90-%EA%B0%80%EC%A7%80%EC%97%90-%EC%A7%91%EC%A4%91%ED%95%9C-%EC%9D%B4%EC%9C%A0-%EA%B7%B8%EB%A6%AC%EA%B3%A0-AI-Loop)

### [Mini React](https://github.com/ndh5178/week5_webcoding)

함수형 컴포넌트, Virtual DOM, useState·useEffect·useMemo를 직접 구현하며 React의 렌더링과 Hook 상태 관리 원리를 학습했습니다.

[학습 기록](https://app2.tistory.com/entry/5%EC%A3%BC%EC%B0%A8-WIL)

### [Pintos](https://github.com/cjsan30/SW-Jungle-W11-VM)

64개 우선순위 FIFO Ready Queue, 프로세스 spawn 동기화, Hash 기반 SPT와 Lazy Loading을 구현하며 운영체제의 스케줄링·프로세스·가상 메모리를 학습했습니다.

## Education & Activity

- **크래프톤 정글 SW-AI 12기** · 2026.03–2026.07
- **국립순천대학교 컴퓨터공학과 졸업** · 2026.02
- **전남 배드민턴 클럽 경기이사** · 2025.01–2026.02
