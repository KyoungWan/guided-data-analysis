# Guided Data Analysis

흩어진 데이터를 분석하면서 사용자와 단계마다 이해를 맞추는 Codex 스킬입니다.

## 주요 기능

- 분석 전 목적·배경·독자·기한·보고 형식 확인
- 파일별 요약과 실제 한 행을 자연스러운 문장으로 설명
- 데이터 품질 점검, 병합 검증, 가설 검증 및 보고서 작성
- 담당자에게 전달할 질문 문안 제안과 답변 반영
- 단계별 설명과 판단 근거 기록

## 설치

```bash
git clone https://github.com/KyoungWan/guided-data-analysis.git ~/.codex/skills/guided-data-analysis
```

같은 경로에 기존 스킬이 있으면 먼저 다른 위치에 보관하세요. 설치 후 새 Codex 대화에서 사용합니다.

## 사용

```text
$guided-data-analysis 이 과제의 데이터 분석을 주도하고 단계마다 핵심 근거를 설명해줘.
```

스킬은 담당자에게 직접 연락하지 않고, 사용자가 전달할 질문 문안을 제공합니다.

## 업데이트

```bash
git -C ~/.codex/skills/guided-data-analysis pull --ff-only
```

상세 지침은 [SKILL.md](SKILL.md)를 참고하세요.
