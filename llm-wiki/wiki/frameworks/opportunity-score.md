---
type: framework
title: 기회점수 — OS · AOS · DOS
grade: mixed
sources:
  - 06-market-opportunity-score/methodology.md
  - 06-market-opportunity-score/methodology-dos.md
updated: 2026-08-18
---
# 기회점수 (Opportunity Score)

Pain을 **중요도와 만족도의 격차**로 점수화해 우선순위를 만든다.

## 정의

- **Importance (I, 1~3):** 목표 달성에 얼마나 필수적인가 (3 필수 / 2 중요 / 1 부차적)
- **Satisfaction (S, 1~3):** 현재 대체 수단으로 얼마나 만족하는가 (1 매우 불만 / 3 만족)
- **AOS** = `I + max(I − S, 0)` — 범위 1.00~3.00. 3.00 = 결핍 극대화
- **DOS** = `AOS × 세그먼트 시장 가중치(Market Relevance)`

## AOS와 DOS를 함께 읽는 이유

**AOS는 순위를 주지, 크기를 주지 않는다.** 결핍이 아무리 커도 그 집단이 작으면 사업이 되지 않는다. DOS는 여기에 시장 비중을 곱해 크기를 되돌린다.

콕집에서 이 차이가 실제로 갈렸다 — [[pp-e2]]와 [[pp-a1]]은 AOS 3.00(공동 1위)이지만 DOS는 0.45로 급락한다. 반면 [[pp-3]]은 AOS·DOS 모두 3.00으로 **유일하게 두 축에서 1위**다.

> ⚠️ **경고 (원본 방법론):** MR(Market Relevance)이 결론을 삼킨다. 가중치 설정이 곧 답을 정한다.

## 사분면

| 사분면 | 의미 | 처분 |
|---|---|---|
| **Q1** 높은 I · 낮은 S | 최고 기회 (Underserved) | MVP 집중 |
| **Q2** 낮은 I · 높은 S | 과잉 만족 (Over-served) | **자원 투입 금지** |
| Q4 | 적정 | 유지 |

콕집의 Q2 함정: [[pp-4]] (무료 도구 탐색, S=3) — *"더 뛰어난 AI 요약"으로 경쟁하려 하면 자본 낭비*.

## 게이트 트랙 — 점수화하지 않는 것

**"충족되지 않으면 비즈니스 자체가 차단되는"** 입장권 성격의 Pain은 순위 산출 대상이 아니다. 콕집에서 6~7건. → [[gate-pains]]

## 연결
[[customer-journey]] · [[pain-register]] · [[persona-spectrum]]
