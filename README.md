# 고민주

### 프론트엔드 개발자

> React와 Next.js로 사용자 흐름과 상태를 설계하고, 외부 API 데이터를 검증 가능한 화면 경험으로 연결합니다.  
> Server/Client 경계부터 runtime validation, 테스트·접근성·CI까지 사용자에게 전달되는 흐름 전체의 품질을 확인합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?logo=notion)](https://app.notion.com/p/3d1622cea8638039bc0be9dcd7832e44)
[![TripFinder](https://img.shields.io/badge/TripFinder-Live-000000?logo=vercel)](https://trip-finder-mauve.vercel.app/)

![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?logo=javascript&logoColor=F7DF1E)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)

## 대표 프로젝트

| 프로젝트 | 개인 기여·문제 해결 | 검증 근거 |
|---|---|---|
| [**TripFinder**](https://github.com/minjuko/trip-finder) | Next.js Server/Client 경계 설계 · TourAPI runtime validation/정규화 · URL 기반 탐색 상태 | [Production](https://trip-finder-mauve.vercel.app/) · 154 tests · Playwright+axe E2E 12개 시나리오 · [CI](https://github.com/minjuko/trip-finder/actions/workflows/ci.yml) |
| [**뽀득뽀득**](https://github.com/minjuko/ppodeuk-user-frontend) | 사용자 예약 흐름 구현 · 종속 상태 초기화 · 시간 규칙 순수 함수 분리 | [예약 규칙 검증](https://github.com/minjuko/ppodeuk-user-frontend/blob/main/docs/refactoring.md) · 105 tests · [CI](https://github.com/minjuko/ppodeuk-user-frontend/actions/workflows/ci.yml) |
| [**농업코파일럿**](https://github.com/minjuko/farm-copilot) | 공통 UI·인증·커뮤니티 구현 · 팀의 AI·공공데이터 API를 화면 흐름으로 연결 | 개인 Fork 기준 Frontend 183 tests · Backend 회귀 검증 138 tests · [CI](https://github.com/minjuko/farm-copilot/actions/workflows/ci.yml) |
| [**TransMate**](https://github.com/minjuko/transmate) | 졸업논문 팀 프로젝트 · 전문용어 데이터셋 구축 · AWS EC2 실행 환경 구성 | 팀의 Spring·AWS Translate 연동 · Backend 56 / Mobile 16 tests · [CI](https://github.com/minjuko/transmate/actions) |

> 테스트·CI·보안 감사와 Backend 회귀 검증은 팀 프로젝트 종료 후 개인적으로 보완한 작업이며, AI 모델과 팀 전체 Backend 구현은 개인 기여에 포함하지 않습니다.

> **뽀득뽀득 관련 저장소:** [USER Frontend](https://github.com/minjuko/ppodeuk-user-frontend) · [OWNER Frontend](https://github.com/minjuko/ppodeuk-owner-frontend) · [Backend](https://github.com/minjuko/ppodeuk-backend). 예약 사용자 흐름은 주요 개인 담당이며, Backend의 팀 당시 원구현은 개인 성과가 아닙니다. Backend 테스트·CI 정비는 프로젝트 종료 후 수행한 개인 개선입니다.

## 핵심 구현 기록

- [TourAPI 응답을 Zod → Normalizer → Domain Model로 분리한 TripFinder](https://github.com/minjuko/trip-finder#설계와-문제-해결)
- [Next.js Server / Client Component 경계와 URL Search Params 설계](https://github.com/minjuko/trip-finder#핵심-역량)
- [예약 규칙을 UI에서 분리하고 회귀 테스트로 고정한 기록](https://github.com/minjuko/ppodeuk-user-frontend/blob/main/docs/refactoring.md)
- [상품 ID를 Query Key에 포함해 캐시 정체성을 분리한 코드 리뷰](https://github.com/Kakao-tech-campus-FE/step2-FE-kakao-shop/pull/197)

## 기술

| 영역 | 기술 |
|---|---|
| 프론트엔드 | Next.js · React · TypeScript · JavaScript · HTML5 · CSS3 · Tailwind CSS |
| 상태·데이터 | URL Search Params · Redux Toolkit · TanStack Query (React Query) · Zod |
| 품질 | Vitest · Jest · React Testing Library · Playwright · axe-core · MSW · GitHub Actions |
| API·Backend 협업 | REST API · Axios · Spring Boot API 회귀 검증 · Django API 계약 테스트 |
| 협업 | Git · GitHub · Notion |
| 배포 경험 | Vercel · Railway · AWS · Docker |

## 추가 프로젝트

- [**카카오 쇼핑하기**](https://github.com/minjuko/kakao-shopping-frontend) — 교육 프로그램 개인 구현 · Redux Toolkit·TanStack Query 상태 관리 · 81 tests · [PR 기반 코드 리뷰](https://github.com/Kakao-tech-campus-FE/step2-FE-kakao-shop/pull/197)
- [**CAMPSTER**](https://github.com/minjuko/campster) — KoChat 대화 상태를 모바일 Frontend Interaction으로 연결
- [**타부러**](https://github.com/minjuko/tabureo-carpool) — 모바일 카풀 UI · TMAP 경로 API 지도 시각화
