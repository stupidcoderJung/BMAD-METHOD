
# BMad Method & BMad Core

[![Stable Version](https://img.shields.io/npm/v/bmad-method?color=blue&label=stable)](https://www.npmjs.com/package/bmad-method)
[![Alpha Version](https://img.shields.io/npm/v/bmad-method/alpha?color=orange&label=alpha)](https://www.npmjs.com/package/bmad-method)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)](https://nodejs.org)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da?logo=discord&logoColor=white)](https://discord.gg/gk8jAdXWmj)

## 버그 수정부터 엔터프라이즈까지 확장 가능한 AI 기반 애자일 개발

**19개의 전문 AI 에이전트**와 프로젝트의 복잡도에 따라—간단한 버그 수정부터 엔터프라이즈 플랫폼까지—유연하게 적응하는 **50개 이상의 가이드 워크플로우**를 통해 **꿈을 설계하고 더 많이 구축하세요(Build More, Architect Dreams - BMAD).**

> **🚀 v6는 v4에 비해 엄청난 업그레이드입니다!** 아키텍처의 완전한 개편, 규모 적응형 지능, 시각적 워크플로우, 그리고 강력한 BMad Core 프레임워크가 도입되었습니다. v4 사용자 여러분, 모든 것이 바뀌었습니다. [새로운 기능 확인하기 →](#whats-new-in-v6)

> **📌 v6 알파(Alpha) 상태:** 베타(Beta)에 가까운 품질로 안정성이 크게 향상되었습니다. 문서는 마무리 단계에 있습니다. 새로운 영상이 곧 [BMadCode YouTube](https://www.youtube.com/@BMadCode)에 업로드될 예정입니다.

## 🎯 왜 BMad Method인가요?

일반적인 AI 코딩 어시스턴트와 달리, BMad Method는 애자일 개발을 이해하는 전문 에이전트가 지원하는 **구조화되고 검증된 워크플로우**를 제공합니다. 각 에이전트는 제품 관리(PM)부터 아키텍처, 테스팅에 이르기까지 깊이 있는 도메인 전문 지식을 갖추고 있으며 매끄럽게 협업합니다.

**✨ 핵심 이점:**

- **규모 적응형 지능 (Scale-Adaptive Intelligence)** - 버그 수정부터 엔터프라이즈 시스템까지 계획의 깊이를 자동으로 조절
- **전체 개발 수명 주기 (Complete Development Lifecycle)** - 분석 → 기획 → 아키텍처 → 구현
- **전문화된 전문성** - 특정 역할을 가진 19명의 에이전트 (PM, 아키텍트, 개발자, UX 디자이너 등)
- **검증된 방법론** - AI로 강화된 애자일 베스트 프랙티스 기반 구축
- **IDE 통합** - Claude Code, Cursor, Windsurf, VS Code와 호환

## 🏗️ BMad Core의 힘

**BMad Method**는 사실 **BMad Core** (**C**ollaboration **O**ptimized **R**eflection **E**ngine, 협업 최적화 성찰 엔진) 위에 구축된 정교한 모듈입니다. 이 혁신적인 아키텍처는 다음을 의미합니다:

- **BMad Core**는 인간-AI 협업을 위한 보편적인 프레임워크를 제공합니다.
- **BMad Method**는 Core를 활용하여 애자일 개발 워크플로우를 제공합니다.
- **BMad Builder**를 사용하면 BMad Method만큼 강력한 사용자 정의 모듈을 직접 만들 수 있습니다.

**BMad Builder**를 사용하면 단순한 에이전트부터 매우 복잡한 도메인 특화 모듈(법률, 의료, 금융, 교육, 창작)까지 설계할 수 있으며, 곧 **공식 커뮤니티 마켓플레이스**에서 공유할 수 있게 됩니다. 당신만의 전문 AI 팀을 만들고 공유하는 것을 상상해 보세요!

## 📊 실제 작동 모습

<p align="center">
  <img src="./src/modules/bmm/docs/images/workflow-method-greenfield.svg" alt="BMad Method Workflow" width="100%">
</p>

<p align="center">
  <em>모든 단계, 에이전트, 결정 지점을 보여주는 전체 BMad Method 워크플로우</em>
</p>

## 🚀 3단계로 시작하기

### 1. BMad Method 설치

```bash
# v6 Alpha 설치 (권장)
npx bmad-method@alpha install

# 또는 프로덕션용 안정화 버전 v4
npx bmad-method install
```

### 2. 프로젝트 초기화

IDE에서 아무 에이전트나 로드한 후 다음을 실행하세요:

```
*workflow-init
```

이 명령어는 프로젝트를 분석하고 적합한 워크플로우 트랙을 추천합니다.

### 3. 트랙 선택

BMad Method는 세 가지 지능형 트랙을 통해 사용자의 니즈에 적응합니다:

| 트랙 | 용도 | 기획 범위 | 시작 소요 시간 |
| ------------------ | ------------------------- | ----------------------- | ------------- |
| **⚡ 퀵 플로우 (Quick Flow)** | 버그 수정, 작은 기능 | 기술 명세서(Tech spec)만 작성 | 5분 미만 |
| **📋 BMad Method** | 제품, 플랫폼 | PRD + 아키텍처 + UX | 15분 미만 |
| **🏢 엔터프라이즈 (Enterprise)** | 규정 준수, 대규모 확장 | 전체 거버넌스 제품군 | 30분 미만 |

> **확실하지 않으신가요?** `*workflow-init`을 실행하여 BMad가 프로젝트 목표를 분석하도록 하세요.

## 🔄 작동 방식: 4단계 방법론

BMad Method는 검증된 개발 수명 주기를 통해 여러분을 안내합니다:

1. **📊 분석 (Analysis)** (선택 사항) - 브레인스토밍, 리서치, 솔루션 탐색
2. **📝 기획 (Planning)** - PRD, 기술 명세서 또는 게임 디자인 문서 작성
3. **🏗️ 솔루션 도출 (Solutioning)** - 아키텍처, UX, 기술적 접근 방식 설계
4. **⚡ 구현 (Implementation)** - 지속적인 검증이 동반되는 스토리 중심 개발

각 단계에는 탁월한 결과를 제공하기 위해 협력하는 전문 워크플로우와 에이전트가 있습니다.

## 🤖 팀을 소개합니다

협력하여 일하는 **12명의 전문 에이전트**:

| 개발 (Development) | 아키텍처 (Architecture) | 제품 (Product) | 리더십 (Leadership) |
| ----------- | -------------- | ------------- | -------------- |
| 개발자 (Developer) | 아키텍트 (Architect) | PM (Product Manager) | 스크럼 마스터 (Scrum Master) |
| UX 디자이너 | 테스트 아키텍트 (Test Architect) | 분석가 (Analyst) | BMad 마스터 (BMad Master) |
| 테크니컬 라이터 | 게임 아키텍트 | 게임 디자이너 | 게임 개발자 |

**테스트 아키텍트(Test Architect)**는 프로덕션 준비가 완료된 픽스처(fixture) 기반 유틸리티를 위해 `@seontechnologies/playwright-utils`와 통합됩니다.

각 에이전트는 깊은 전문성을 가지고 있으며 팀의 스타일에 맞게 커스터마이징할 수 있습니다.

## 📦 포함된 내용

### 핵심 모듈 (Core Modules)

- **BMad Method (BMM)** - 완전한 애자일 개발 프레임워크
  - 12명의 전문 에이전트
  - 4단계에 걸친 34개의 워크플로우
  - 규모 적응형 기획
  - [→ 문서 허브](./src/modules/bmm/docs/README.md)

- **BMad Builder (BMB)** - 사용자 정의 에이전트 및 워크플로우 생성
  - 단순 에이전트부터 복잡한 모듈까지 무엇이든 구축
  - 도메인 특화 솔루션 생성 (법률, 의료, 금융, 교육)
  - 곧 출시될 커뮤니티 마켓플레이스에 창작물 공유
  - [→ 빌더 가이드](./src/modules/bmb/README.md)

- **Creative Intelligence Suite (CIS)** - 혁신 및 문제 해결
  - 브레인스토밍, 디자인 씽킹, 스토리텔링
  - 5가지 창의적 퍼실리테이션 워크플로우
  - [→ 창의적 워크플로우](./src/modules/cis/README.md)

### 주요 기능

- **🎨 커스터마이징 가능한 에이전트** - 성격, 전문성, 커뮤니케이션 스타일 수정 가능
- **🌐 다국어 지원** - 커뮤니케이션과 코드 출력을 위한 설정을 분리하여 지원
- **📄 문서 샤딩 (Document Sharding)** - 대규모 프로젝트에서 토큰 90% 절약
- **🔄 업데이트 안전성 (Update-Safe)** - 업데이트 후에도 사용자 설정 유지
- **🚀 웹 번들 (Web Bundles)** - ChatGPT, Claude Projects, Gemini Gems에서 사용 가능

## 📚 문서 (Documentation)

### 빠른 링크

- **[빠른 시작 가이드](./src/modules/bmm/docs/quick-start.md)** - 15분 소개
- **[전체 BMM 문서](./src/modules/bmm/docs/README.md)** - 모든 가이드 및 참조
- **[에이전트 커스터마이징](./docs/agent-customization-guide.md)** - 나만의 에이전트 만들기
- **[모든 문서](./docs/index.md)** - 전체 문서 색인

### v4 사용자를 위한 안내

- **[v4 문서](https://github.com/bmad-code-org/BMAD-METHOD/tree/V4)**
- **[v4에서 v6로 업그레이드 가이드](./docs/v4-to-v6-upgrade.md)**

## 💬 커뮤니티 및 지원

- **[Discord 커뮤니티](https://discord.gg/gk8jAdXWmj)** - 도움 받기, 프로젝트 공유
- **[GitHub Issues](https://github.com/bmad-code-org/BMAD-METHOD/issues)** - 버그 제보, 기능 요청
- **[YouTube 채널](https://www.youtube.com/@BMadCode)** - 비디오 튜토리얼 및 데모
- **[웹 번들](https://bmad-code-org.github.io/bmad-bundles/)** - 사전에 빌드된 에이전트 번들

## 🛠️ 개발

BMad 코드베이스에 기여하는 개발자를 위한 명령어:

```bash
# 모든 품질 검사 실행
npm test

# 개발 명령어
npm run lint:fix      # 코드 스타일 수정
npm run format:fix    # 코드 자동 포맷팅
npm run bundle        # 웹 번들 빌드
```

전체 개발 가이드라인은 [CONTRIBUTING.md](CONTRIBUTING.md)를 참조하세요.

## v6의 새로운 기능 (What's New in v6)

**v6는 v4에서의 완전한 아키텍처 혁명을 의미합니다:**

### 🚀 주요 업그레이드

- **BMad Core 프레임워크** - 맞춤형 도메인 솔루션을 가능하게 하는 모듈식 아키텍처
- **규모 적응형 지능** - 버그 수정부터 엔터프라이즈까지 자동 조정
- **시각적 워크플로우** - 전체 방법론을 보여주는 아름다운 SVG 다이어그램
- **BMad Builder 모듈** - 나만의 AI 에이전트 팀 생성 및 공유
- **50개 이상의 워크플로우** - v4의 20개에서 증가, 모든 개발 시나리오 커버
- **19명의 전문 에이전트** - 커스터마이징 가능한 성격과 전문성으로 강화됨
- **업데이트 안전 커스터마이징** - 모든 업데이트 후에도 설정 유지
- **웹 번들** - ChatGPT, Claude, Gemini에서 에이전트 사용 가능
- **다국어 지원** - 커뮤니케이션과 코드를 위한 분리된 설정
- **문서 샤딩** - 대규모 프로젝트를 위한 90% 토큰 절약

### 🔄 v4 사용자를 위한 안내

- **[포괄적 업그레이드 가이드](./docs/v4-to-v6-upgrade.md)** - 단계별 마이그레이션
- **[v4 문서 아카이브](https://github.com/bmad-code-org/BMAD-METHOD/tree/V4)** - 레거시 참조
- 가능한 경우 하위 호환성 유지
- 설치 프로그램 감지를 통한 원활한 마이그레이션 경로 제공

## 📄 라이선스

MIT 라이선스 - 자세한 내용은 [LICENSE](LICENSE)를 참조하세요.

**상표 고지:** BMAD™ 및 BMAD-METHOD™는 BMad Code, LLC의 상표입니다.

---

<p align="center">
  <a href="https://github.com/bmad-code-org/BMAD-METHOD/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=bmad-code-org/BMAD-METHOD" alt="Contributors">
  </a>
</p>

<p align="center">
  <sub>인간-AI 협업 커뮤니티를 위해 ❤️로 만들었습니다.</sub>
</p>
