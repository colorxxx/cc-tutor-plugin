# cc-tutor — Claude Code 초보자 튜터 플러그인

Claude Code를 처음 쓰는 사람을 위한 **질문 중심 튜터**입니다.
설명을 듣는 게 아니라, 질문에 답하면서 스스로 깨닫는 방식으로 진행됩니다.

## 무엇을 배우나요?

| 레슨 | 주제 |
|---|---|
| L0 | 암묵지 + 하니스 — "규칙을 파일에 적으면 작동한다" |
| L1 | 첫 번째 Skill — SKILL.md 구조 |
| L2 | 컨텍스트 관리 — 토큰, 작업대, "필요한 것만 로드" |
| L3 | 템플릿 — 양식 고정 + 검증 체크리스트 |
| L4 | Subagent 검증 — "검증은 깨끗한 새 AI가 한다" |
| L4.5 | MCP 맛보기 — AI에게 도구 달아주기 |
| L5 | 졸업과제 — 내 업무 스킬 직접 만들기 |

체험용 예제 스킬 4개(mail-polish, memo-clean, notice-maker, docs-lookup)가 함께 들어 있어
각 레슨에서 배운 개념을 바로 발동해 볼 수 있습니다.

## 설치 (2줄)

Claude Code 안에서:

```
/plugin marketplace add colorxxx/cc-tutor-plugin
/plugin install cc-tutor@cc-tutor
```

## 시작하기

설치 후 Claude Code에서 이렇게 말하면 됩니다:

```
cc-tutor로 수업 시작해줘
```

첫 세션에서 진도판(`~/.claude/cc-tutor-progress/`)이 자동으로 만들어지고,
이후 세션에서는 이어서 진행됩니다.

## 업데이트

```
/plugin marketplace update cc-tutor
```

학습 진도는 플러그인 바깥(`~/.claude/cc-tutor-progress/`)에 저장되므로
업데이트해도 진도는 유지됩니다.

## 라이선스

MIT
