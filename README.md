# SmartLinkWeb
26년도 1학기 기업연계 캡스톤디자인 웹 프론트엔드

**반도체 후공정 비전 검사 장비 모니터링 웹 대시보드**

## 프로젝트 개요

반도체 후공정 비전 검사 장비의 운영 현황과 검사 데이터를 시각적으로 확인할 수 있는 웹 대시보드 프로젝트입니다.

Web-Backend REST API를 통해 장비별 KPI, 검사 결과, 수율 및 불량 통계 등을 조회하며, 장비 운영 현황과 AI 기반 분석 보고서를 확인할 수 있도록 구현했습니다.

## 프로젝트 정보

| 항목 | 내용 |
|---|---|
| Project | Smart Link Web |
| Category | Web Frontend |
| Role | Frontend Developer |
| Framework | React 18 |
| Language | TypeScript |
| Bundler | Vite |
| State Management | Zustand |
| UI | Tailwind CSS, shadcn/ui |
| Chart | Recharts |
| HTTP Client | Axios |

## 주요 기능

### 1. Dashboard
- 전체 장비 KPI 요약
- 수율(Yield) 트렌드 시각화
- 불량 유형별 분포 확인
- 주요 검사 데이터 및 통계 정보 제공

### 2. Equipment Status
- 장비별 상세 통계 및 운영 현황 조회
- SPC 히트맵 시각화
- 장비 가동률(Uptime) 확인
- AI 기반 분석 인사이트 제공

### 3. AI Report
- AI 기반 일별 및 주간 분석 보고서 조회
- Overview, Quality, Operations 영역별 보고서 제공
- 보고서 요약 및 상세 데이터 시각화
- 보고서 전용 레이아웃 구성

## 담당 업무 및 기여

**Frontend Development (프론트엔드 전반 담당)**

- React 18과 TypeScript를 활용한 웹 프론트엔드 전반 개발
- 기능별 UI 컴포넌트 분리 및 재사용 가능한 화면 구조 구성
- 장비별 운영 현황과 검사 결과를 확인할 수 있는 대시보드 UI 구현
- 테이블, KPI 카드, 차트 등 데이터 시각화 컴포넌트 구현
- Axios 기반 REST API 연동 및 비동기 데이터 조회 기능 구현
- 조회 조건에 따른 API 요청 파라미터 구성 및 서버 응답 데이터 처리
- 백엔드에서 전달받은 데이터를 활용한 동적 화면 구성
- Zustand를 활용한 상태 관리
- 장비 모니터링 및 AI 분석 보고서 요약 페이지 구현
- 보고서 데이터의 시각적 전달을 위한 화면 레이아웃 구성

## 원본 프로젝트

본 프로젝트의 소스 코드 및 전체 구현 내용은 아래 원본 Repository에서 확인할 수 있습니다.

**[Smart Link Web - Original Repository](https://github.com/web-capstone-ds/smart-link-web)**

---
