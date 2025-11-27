
# BMM - BMad 방법론 모듈

전문 에이전트와 워크플로우를 통해 포괄적인 수명 주기(Lifecycle) 관리를 제공하는 AI 기반 애자일 개발을 위한 핵심 오케스트레이션 시스템입니다.

---

## 📚 전체 문서 (Complete Documentation)

👉 **[BMM 문서 허브](./docs/README.md)** - 전체 가이드, 튜토리얼, 참고 자료를 보려면 여기에서 시작하세요.

**빠른 링크:**

- **[빠른 시작 가이드](./docs/quick-start.md)** - BMad가 처음이신가요? 여기서 시작하세요 (15분)
- **[에이전트 가이드](./docs/agents-guide.md)** - 12명의 전문 AI 에이전트 만나보기 (45분)
- **[규모 적응형 시스템](./docs/scale-adaptive-system.md)** - BMM이 프로젝트 규모에 적응하는 방법 (42분)
- **[FAQ](./docs/faq.md)** - 자주 묻는 질문에 대한 빠른 답변
- **[용어집](./docs/glossary.md)** - 주요 용어 참조

---

## 🏗️ 모듈 구조 (Module Structure)

이 모듈의 구성은 다음과 같습니다:

```
bmm/
├── agents/          # 12명의 전문 AI 에이전트 (PM, Architect, SM, DEV, TEA 등)
├── workflows/       # 4단계 + 테스팅에 걸친 34개의 워크플로우
├── teams/           # 사전 구성된 에이전트 그룹
├── tasks/           # 원자적(Atomic) 작업 단위
├── testarch/        # 포괄적인 테스팅 인프라
└── docs/            # 전체 사용자 문서
```

### 에이전트 명단 (Agent Roster)

**핵심 개발:** PM, Analyst(분석가), Architect(아키텍트), SM(스크럼 마스터), DEV(개발자), TEA(테스트 엔지니어링 아키텍트), UX Designer(UX 디자이너), Technical Writer(테크니컬 라이터)
**게임 개발:** Game Designer(게임 기획자), Game Developer(게임 개발자), Game Architect(게임 아키텍트)
**오케스트레이션:** BMad Master (Core에서 제공)

👉 **[전체 에이전트 가이드](./docs/agents-guide.md)** - 역할, 워크플로우, 각 에이전트 사용 시기

### 워크플로우 단계 (Workflow Phases)

**0단계:** 문서화 (브라운필드 전용)
**1단계:** 분석 (선택 사항) - 5개 워크플로우
**2단계:** 기획 (필수) - 6개 워크플로우
**3단계:** 솔루션 도출 (레벨 3-4) - 2개 워크플로우
**4단계:** 구현 (반복적) - 10개 워크플로우
**테스팅:** 품질 보증 (병렬 진행) - 9개 워크플로우

👉 **[워크플로우 가이드](./docs/README.md#-workflow-guides)** - 각 단계별 상세 문서

---

## 🚀 시작하기 (Getting Started)

**신규 프로젝트:**

```bash
# BMM 설치
npx bmad-method@alpha install

# IDE에서 Analyst 에이전트 로드 후 실행:
*workflow-init
```

**기존 프로젝트 (브라운필드):**

```bash
# 먼저 코드베이스 문서화
*document-project

# 그 다음 초기화
*workflow-init
```

👉 **[빠른 시작 가이드](./docs/quick-start.md)** - 전체 설정 및 첫 프로젝트 튜토리얼

---

## 🎯 핵심 개념 (Key Concepts)

### 규모 적응형 설계 (Scale-Adaptive Design)

BMM은 프로젝트 복잡도(레벨 0-4)에 따라 자동으로 조정됩니다:

- **레벨 0-1:** 버그 수정 및 소규모 기능을 위한 Quick Spec Flow
- **레벨 2:** 아키텍처(선택 사항)가 포함된 PRD
- **레벨 3-4:** 전체 PRD + 포괄적인 아키텍처

👉 **[규모 적응형 시스템](./docs/scale-adaptive-system.md)** - 전체 레벨 분석

### 스토리 중심 구현 (Story-Centric Implementation)

스토리는 정의된 수명 주기를 거칩니다: `백로그 → 초안 → 개발 준비 → 진행 중 → 검토 → 완료`

적시(Just-in-time) 에픽 컨텍스트 및 스토리 컨텍스트는 필요할 때 정확한 전문 지식을 제공합니다.

👉 **[구현 워크플로우](./docs/workflows-implementation.md)** - 전체 스토리 수명 주기 가이드

### 멀티 에이전트 협업 (Multi-Agent Collaboration)

파티 모드를 사용하여 전략적 결정, 창의적 브레인스토밍, 복잡한 문제 해결을 위한 그룹 토론에 19명 이상의 모든 에이전트(BMM, CIS, BMB, 커스텀 모듈 포함)를 참여시키세요.

👉 **[파티 모드 가이드](./docs/party-mode.md)** - 멀티 에이전트 협업 조율 방법

---

## 📖 추가 리소스 (Additional Resources)

- **[브라운필드 가이드](./docs/brownfield-guide.md)** - 기존 코드베이스 작업
- **[Quick Spec Flow](./docs/quick-spec-flow.md)** - 레벨 0-1 프로젝트를 위한 패스트 트랙
- **[엔터프라이즈 에이전트 개발](./docs/enterprise-agentic-development.md)** - 팀 협업 패턴
- **[문제 해결](./docs/troubleshooting.md)** - 일반적인 문제 및 해결책
- **[IDE 설정 가이드](../../../docs/ide-info/)** - Claude Code, Cursor, Windsurf 등 구성 방법

---

## 🤝 커뮤니티 (Community)

- **[Discord](https://discord.gg/gk8jAdXWmj)** - 도움 받기, 피드백 공유 (#general-dev, #bugs-issues)
- **[GitHub Issues](https://github.com/bmad-code-org/BMAD-METHOD/issues)** - 버그 신고 또는 기능 요청
- **[YouTube](https://www.youtube.com/@BMadCode)** - 비디오 튜토리얼 및 설명

---

**빌드할 준비가 되셨나요?** → [빠른 시작 가이드로 이동](./docs/quick-start.md)
