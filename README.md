# 프로젝트 소개서

이 레포지토리는 다양한 실전 프로젝트 및 클론코딩 작업을 기반으로 구성되어 있으며, Next.js, React, Express, MariaDB, Tailwind 등 최신 웹 기술을 실무 환경에 접목시킨 예제들로 구성되어 있습니다.

---

## 🏟️ 풍산멀티스포츠센터
- **도메인**: [www.yjins-aws.com](http://www.yjins-aws.com)
- **서비스 유형**: 실제 운영 중인 상업용 웹서비스
- **기술 스택**:
  - Docker + EC2 (AWS)
  - MariaDB
  - Next.js (React 기반 SSR/CSR 통합 프레임워크)
  - Express (Node.js 백엔드)
  - TypeScript
  - Tailwind CSS + CSS Module
  - GitHub Actions (CI/CD 자동 배포)
  - 상태관리: Zustand + React Context
  - FastAPI (Python 기반 API)
  - GPT API 연동
  - Swagger 문서 자동화
- **특이사항**:
  - 기존 jQuery 기반 웹사이트를 Next.js 기반 SPA/SSR 앱으로 전면 마이그레이션
  - 다양한 API 및 인증처리, 백오피스 관리기능 포함

---

## 💰 머니핀
- **서비스 유형**: 웹 기반 금융 데이터 뷰어 앱
  -`git` : https://github.com/summercider/NextProject
- **기술 스택**:
  - Next.js
  - SSR + CSR 분리 아키텍처 설계
  - 기존 `MSW(Mock Service Worker)` 제거
  - 공공데이터포털 API 직접 연동 (GET + POST 처리)
- **특이사항**:
  - 클라이언트 요청 흐름에 따라 SSR과 CSR을 분리 구성
  - 실데이터 연동 및 쿼리 최적화

---

## 🍽️ 롯데이츠 클론
- **배포 URL**: [react-project-mu-six.vercel.app](https://react-project-mu-six.vercel.app)
- **기술 스택**:
  - React.js
  - JavaScript (Vanilla)
  - MSW (Mock Service Worker) 기반 목데이터 구성
- **특이사항**:
  - 실제 롯데이츠 UI/UX를 반영한 클론 코딩
  - 컴포넌트 구조 최적화 및 반복 요소 분리

---

## 🏢 LH 토지공사 반응형 웹
- **기술 스택**:
  - React.js
  - 반응형 디자인 (모바일/PC 대응)
- **특이사항**:
  - 퍼블리싱과 컴포넌트 분리 전략 중심
  - 공공기관 스타일 가이드에 맞춘 반응형 UI 설계

---

## 📌 기타 정보
- 모든 프로젝트는 버전 관리와 협업을 고려한 구조로 작성되었으며, 각 환경에서 `Lint`, `Prettier`, `CI/CD` 설정을 포함하고 있습니다.
- 일부 프로젝트는 실시간 GPT API 및 공공 API와 연동되며, 인증 처리와 보안 정책을 반영하였습니다.

---

> 🔧 문의 및 협업 제안은 PR 또는 Issues로 남겨주세요.
