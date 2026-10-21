# 고민주 | Software Engineer

프론트엔드 개발을 중심으로 **서비스 흐름과 상태를 설계**하고, **API 연동·데이터 정합성·자동화 테스트**를 통해 기능의 안정성을 검증합니다. 팀 프로젝트 이후에도 백엔드 예약·결제 로직, AI 서비스 연동과 실행 환경을 개선하며 개발 범위를 확장하고 있습니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?logo=notion)](https://app.notion.com/p/3fd622cea863815091ede6ed72c5170c)
[![TripFinder](https://img.shields.io/badge/TripFinder-Live-000000?logo=vercel)](https://trip-finder-mauve.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-555555?logo=gmail&logoColor=white)](mailto:minjuko.id@gmail.com)

## 핵심 역량

- **서비스 로직·상태 관리:** 예약 단계별 종속 상태 및 시간 구간 검증, URL 기반 검색 상태 설계
- **시스템·데이터 연동:** REST API 계약·오류 처리, 외부 데이터 검증·정규화, AWS Translate·공공데이터·AI 진단 기능 연동
- **테스트·안정화:** Jest·Vitest·Playwright·JUnit 기반 회귀 검증, GitHub Actions CI, 개발·테스트 환경 분리

## 대표 프로젝트

| 프로젝트 | 담당 역할·주요 개선 | 검증·성과 |
| --- | --- | --- |
| [**뽀득뽀득**](https://github.com/minjuko/ppodeuk-user-frontend) · [Backend](https://github.com/minjuko/ppodeuk-backend) | 6인 팀: 사용자 예약 화면·상태 관리·API 연동. **종료 후 개인 개선:** 예약 구간 검증, 결제 승인 전 JPA 비관적 잠금 조회 및 테스트 환경 보완 | FE **111건** · BE **86건** 테스트 · 예약 규칙 **24건** · 카카오 테크 캠퍼스 **대상(팀)** |
| [**TransMate**](https://github.com/minjuko/transmate) | 3인 팀: 전문용어 데이터·AWS Translate 용어집 구축 및 EC2 배포 주도, 번역 API 공동 연동 | Backend **56건** · Mobile **16건** 테스트 · [CI](https://github.com/minjuko/transmate/actions) |
| [**농업코파일럿**](https://github.com/minjuko/farm-copilot) | 6인 팀: 공통 UI·인증·커뮤니티와 Django·AI·공공데이터 화면 연동. **후속 개선:** API 오류 처리·YOLO 모델 준비 상태 검증 | FE **185건** · BE **227건** 테스트 · 실제 YOLO 격리 통합 테스트 **1건** · KT AIVLE **Collaboration상(팀)** |
| [**TripFinder**](https://github.com/minjuko/trip-finder) · [Live](https://trip-finder-mauve.vercel.app/) | 개인 프로젝트: Next.js Server/Client 경계, TourAPI 응답의 Zod 검증·정규화, URL 검색 상태·E2E 검증 | Vitest **154건** · Playwright E2E **12시나리오** · [CI](https://github.com/minjuko/trip-finder/actions/workflows/ci.yml) |

> 팀 프로젝트 당시 담당 범위와 종료 후 개인 개선을 구분했습니다. 테스트 수치는 각 저장소에 기록된 검증 결과이며, 운영 환경에서의 완전한 동작이나 성능을 의미하지 않습니다. 프로젝트명을 클릭하면 구현·검증 범위와 실행 방법을 확인할 수 있습니다.

## 기술 및 사용 경험

| 영역 | 기술·도구 |
| --- | --- |
| **Languages** | JavaScript · TypeScript · Python · Java · SQL |
| **Frontend** | React · Next.js · Redux Toolkit · TanStack Query · Axios · Zod |
| **Backend·API** | REST API 설계·연동 · Spring Boot/JPA 로직 후속 개선 · Django API 연동 |
| **Cloud·Integrations** | AWS EC2 · AWS Translate · 공공데이터 API · Vercel |
| **Testing·Quality** | Jest · React Testing Library · Vitest · Playwright · JUnit · GitHub Actions CI |

> 프론트엔드 개발이 주요 경험이며, 백엔드·클라우드·AI 관련 항목은 각 프로젝트에서 직접 수행한 작업 또는 연동·검증 범위에 한해 기술했습니다.
