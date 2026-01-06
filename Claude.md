# Claude 작업 로그

> Antigravity 프로젝트의 Claude 협업 기록 및 문서 인덱스

## 📋 최근 세션
- **[2025-01-06](.claude/sessions/2025-01-06.md)** - 프로젝트 구조 정리 및 `.claude` 폴더 시스템 도입
- **[2025-12-14](.claude/sessions/2025-12-14.md)** - 게임 흐름 재구축, 보스전 연출 완성
- **[2025-12-06](.claude/sessions/2025-12-06.md)** - 초기 게임 메카닉 구현, Divider 로직 완성, 배포

## 🎮 프로젝트 정보

### 게임 개요
**Divider**는 숫자의 나눗셈과 뺄셈 규칙을 활용하여 적을 물리치는 퍼즐 전략 디펜스 게임입니다.

- **프로젝트명**: DividerGame
- **플랫폼**: 웹 (모바일 최적화)
- **배포**: [GitHub Pages](https://sirgrey8209.github.io/DividerGame/) _(저장소 변경 후 업데이트 예정)_
- **상태**: 핵심 메카닉 완성, 콘텐츠 확장 단계

### 주요 문서
- **[게임 디자인](.claude/context/game-design.md)** - 게임 규칙, 메카닉, 비주얼 스타일
- **[기술 스택](.claude/context/tech-stack.md)** - React, TypeScript, Vite, Zustand, Framer Motion
- **[코딩 컨벤션](.claude/context/conventions.md)** - 프로젝트 규칙, 패턴, 원칙

## 🚀 다음 작업
- **[개발 로드맵](.claude/plans/roadmap.md)** - 우선순위별 작업 계획

### 우선순위 높음
1. 던전 데이터 실제 연결 및 밸런싱
2. 보상 시스템 구현 (무기 해금, 업그레이드)
3. 사운드 시스템 추가 (SFX, BGM)

## 📁 폴더 구조
```
.claude/
├── sessions/       # 날짜별 작업 로그
├── context/        # 프로젝트 컨텍스트 및 설계 문서
└── plans/          # 계획, 로드맵, TODO
```

## 💡 핵심 게임 규칙
- **나눗셈 (Divider)**: `적 HP % 무기 = 0` 일 때만 `HP / 무기`로 감소
- **뺄셈 (Subtractor)**: 항상 적용, `HP - 무기`
- **즉사 메카닉**: 나눗셈 결과가 1이면 즉시 0으로 처리

## 🔗 빠른 링크
- [프로젝트 README](README.md)
- [게임 플레이](https://sirgrey8209.github.io/DividerGame/) _(저장소 변경 후)_
- [GitHub Repository](https://github.com/sirgrey8209/DividerGame) _(저장소 변경 후)_

## 📝 프로젝트 히스토리
**Note**: 이 프로젝트는 원래 Google Gemini의 Antigravity 기능을 테스트하는 토이 프로젝트로 시작했으나, 독자적인 게임 메카닉을 가진 풀 게임으로 발전했습니다.

---

마지막 업데이트: 2025-01-06
