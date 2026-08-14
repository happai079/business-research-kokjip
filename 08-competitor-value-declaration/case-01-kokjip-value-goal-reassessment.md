# 사례 01 — 「콕집」 가치목표 재검토: Value Proposition 기준점 업데이트

> **콕집** — 국비 교육·대학 강의를 녹음·태깅해, **현직자 관점의 우선순위로 복습할 것만 골라주는** 학습 앱

작성 시점: 2026년 8월 · 역할: Senior Product Strategist 재검토

**입력 문서** — [Ch01 5가지 힘](../01-porters-five-forces/case-01-kokjip-lecture-review-prioritizer.md) · [Ch04 TAM-SAM-SOM](../04-tam-sam-som-market-segment-map/case-01-kokjip-lecture-review-prioritizer.md) · [Ch04 딥리서치](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md) · [Ch06 Pain List](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-pain-list.md) · [Ch06 전략 함의](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md) · [Ch08 경쟁사 가치 선언](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md) · [부록 A-6 종합 판정](../appendix-a-post-ai-learner-pain/verdict-ai-competency-proof-market.md) · [부록 A-2 AI 대체 가능성](../appendix-a-post-ai-learner-pain/ai-substitutability-and-viability.md)

**근거 표기** — 🟢 실측 / 🟡 추론 / 🔴 가설

> **원칙** — 기존 가치목표를 유지해야 한다는 전제를 두지 않았습니다. 세 안 중 하나는 **독립 지위를 잃고**, 하나는 **조건부로만 유지**되며, 하나는 **지금은 쓸 수 없다는 결론이 그대로 유지**됩니다. 억지로 세 안을 대등하게 살리지 않았습니다.

---

## 0. 재검토 대상 — [Ch08 §6-8](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#6-8-콕집이-추구할-차별적-가치-목표--세-방향)의 기존 3안

| 안 | 한 문장 | 참조한 경쟁사 화법 |
|---|---|---|
| **A. 시간** | "부족한 것은 강의가 아니라 당신의 시간이다" | Otter(행동 제거) + 노션(시간축) |
| **B. 출처** | "우선순위는 우리가 정하지 않는다, 강사가 정한다" | Gemini Notebook(근거 범위) + 티로(부정형) + 패스트캠퍼스(권위 위임) |
| **C. 결과** | "먼저 합격한 사람이 실제로 붙잡았던 것부터 보여준다" | 노션(시간이 지나야 쌓이는 자산) |

Ch08의 기존 결론은 "A를 겉면에, B를 같은 화면에, C는 12개월 뒤 예약"이었습니다. 이 문서는 그 결론을 전제로 두지 않고 처음부터 다시 심문합니다.

---

## 1. A안 「시간」

### 1. 기존 가치목표
"복습은 다 하는 게 아니라, 남은 시간 안에 끝내는 것이다. 오늘 쓸 수 있는 시간을 알려주면 그 안에 들어갈 것만 골라준다."

### 2. 현재 유효성
**수정** — 독립 가치목표가 아니라 **B안의 전달 형식(입력 인터페이스)으로 격하**.

### 3. 고객 Pain과의 연결
**PP-3**([Ch06 Pain List §2-2](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-pain-list.md)) — "남은 시간에 무엇을 버릴지 정하고 싶다." 17건 중 **AOS 3.00 · DOS(SAM) 3.00 — 두 지표 모두 공동 1위**([Ch06 전략 §6 종합 처분](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#종합-처분)) 🟢. Pain 연결 자체는 이 문서에서 가장 강합니다.

### 4. Desired Outcome
학습자가 실제로 원하는 것은 "시간을 아는 것"이 아니라 **"6개월 안에 채용될 수준에 도달하는 것"**([Ch06 §2-1](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-pain-list.md#2-1-페르소나별-goal--importance를-매길-기준선))입니다. "시간 안에 무엇을 볼지"는 그 목표로 가는 **수단**이지 목표 자체가 아닙니다. 이 구분이 §8의 약점과 직결됩니다.

### 5. 경쟁사·대체재 대비 차별성
[Ch08 §6-8 A안 표](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#세-방향-비교와-권고) — "시간을 입력으로 받는 사업자는 8곳 중 **0곳**" 🟢. 인터페이스 차원에서는 차별적입니다. 그러나 **복제 난이도가 「낮음」으로 이미 판정**돼 있습니다 — 다글로가 프롬프트 한 줄로 "오늘 시간이 얼마나 있나요?" 입력창을 추가하는 데는 기술 장벽이 없습니다.

### 6. AI에 의해 대체될 가능성
**중~상.** Gemini Notebook은 아직 "시간 예산 내 선별"을 하지 않지만([Ch08 §4-3](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#4-3-gemini-notebookgoogle--콕집이-팔려던-것을-이미-공짜로-나눠주고-있다)), Study Mode·Learning Mode류가 "단계 분해·유도"를 이미 무료로 제공하는 추세([부록 A-2 §1](../appendix-a-post-ai-learner-pain/ai-substitutability-and-viability.md#1-먼저-확정--범용-ai가-2026년-현재-실제로-하는-것))라, "얼마나 시간 있으세요?" 같은 입력창은 **범용 AI 채팅에 프롬프트 한 줄로 재현 가능**합니다 🟡. 이것이 A안을 독립 가치목표로 세우면 안 되는 결정적 이유입니다.

### 7. 이를 뒷받침하는 직접 근거
- PP-3 AOS·DOS 공동 1위 🟢([Ch06 전략 §6](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#종합-처분))
- 8곳 중 시간 입력 사업자 0곳 🟢([Ch08 §6-8](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#세-방향-비교와-권고))
- Ch08 자체 결론 — "A 단독은 임의 절삭으로 보인다" 🟡([Ch08 §6-8 권고](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#세-방향-비교와-권고))

### 8. 근거가 충분하지 않은 부분
- **[Ch06 전략 §8 가정 5](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#8-이-문서가-서-있는-가정)** — "남은 시간 입력"을 학습자가 실제로 쓰는지 미검증 🔴. 입력 자체가 마찰이면 A안은 문법으로는 성립해도 제품에서 작동하지 않습니다.
- "시간 안에 넣을 것"의 **선정 근거가 A안 문장 안에 없습니다.** 이 결핍이 그대로 B안이 채워야 할 자리입니다.

### 9. 최종 가치목표 제안
**독립 가치목표에서 제외.** PP-3라는 최상위 Pain에 접근하는 **진입 화법(프레이밍)**으로만 유지합니다 — "부족한 것은 강의가 아니라 시간"이라는 문장은 첫 화면 카피로 쓰되, 그 뒤에 반드시 B안의 판정 근거가 따라와야 성립하는 **종속 요소**로 재정의합니다.

---

## 2. B안 「출처」

### 1. 기존 가치목표
"무엇이 중요한지는 우리가 판단하지 않는다. 강의 중 강사가 '이건 실무에서 씁니다'라고 말한 순간을 찾아 되돌려 드릴 뿐이다."

### 2. 현재 유효성
**유지 — 단 조건부.** 콕집의 실제 제품 메커니즘([Ch04 딥리서치 §4-2 확정](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#4-2-확정--강사-발화로-출발선을-취업-이력으로-벽을))과 일치하는 유일한 안이며, 세 안 중 유일하게 **판정 근거를 문장 안에 담고 있습니다.**

### 3. 고객 Pain과의 연결
직접 대응하는 단독 Pain은 없지만, **게이트 6건 전체**(PP-K5·PP-E1·PP-E3·PP-N1·PP-N2·PP-N3)가 사실상 "강사가 녹음을 허용하는가" 하나의 관문이라는 것이 [Ch06 §5 교차 Pain](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-pain-list.md#5-교차-pain--한-번-풀면-둘이-풀리는-자리)에서 확인됩니다 🟢. B안은 이 관문을 여는 유일한 화법입니다 — "강사를 평가하지 않는다"는 선언이 없으면 PP-K5·PP-N1은 열리지 않습니다.

### 4. Desired Outcome
세 청중이 원하는 것이 다릅니다. 학습자는 **신뢰할 수 있는 우선순위**(PP-3의 이면), 강사는 **권위 훼손 없는 동의**(PP-K5·PP-N1 해소), 기관은 **감사가 아닌 도입 명분**(PP-K5)을 원합니다. B안은 이 세 Desired Outcome을 **하나의 문장으로 동시에 만족시키는 유일한 안**입니다([Ch08 §6-7 ㉣ 3청중 안전](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#6-7-참조-선언-필터링--여덟-개-중-무엇을-차용할-수-있는가) — B가 유일하게 ◎).

### 5. 경쟁사·대체재 대비 차별성
**가장 강한 근거.** [Ch04 딥리서치 §4](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#4-6단계--차별화-축-재정의) — 녹음·요약·퀴즈·자료정리·오답기반 우선순위는 전부 탈락, **"현직자 실무 기준의 중요도 판정"만 유효 — 확인된 사업자 없음** 🟢. [Ch08 §6-2](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#6-2-여덟-개-선언-어디에도-없는-문장이-하나-있다)도 독립적으로 같은 결론 — 경쟁 8곳 중 "뺄셈(버릴 것을 정해주기)"을 선언한 곳 **0곳**.

### 6. AI에 의해 대체될 가능성
**중.** 기술적으로는 다글로도 ④(강사 발화)를 원리상 시도할 수 있습니다([Ch04 딥리서치 §4-1](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#4-1-판정-근거-후보-4개의-비교)). 그러나 세 가지 이유로 즉시 복제되지 않습니다 — ㉠ 대학생 일반 강의 대상이라 "실무 중요도" 축 자체가 없고 ㉡ KDT 도메인 특화 신호 사전이 필요하며 ㉢ ③(취업 이력)을 만들 수 없어 장기 가중치 교정이 불가능 🟡. **다만 이 빈자리는 "원리적으로 못 함"이 아니라 "지금 우선순위가 아님"이라 언제든 닫힐 수 있다**는 것이 Ch08의 명시적 경고입니다([Ch08 §6-3 ①](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#6-3-그러나-빈자리가-곧-기회는-아니다--세-가지-유보)).

### 7. 이를 뒷받침하는 직접 근거
- 딥리서치 §4-2 — 판정 근거 확정 🟡(추론이나 데이터 구조 분석에 기반)
- Ch08 §6-2 — 8곳 중 뺄셈 선언 0곳 🟡
- Ch06 §5 — 게이트 6건이 사실상 1건 🟢

### 8. 근거가 충분하지 않은 부분
**이 문서에서 가장 무거운 미해소 항목입니다.** [Ch04 딥리서치 §7-1](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#7-미해소-항목)과 [Ch06 전략 §7-①](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#지금-확인할-것--싸고-크게-바꾸는-두-가지)이 **동일한 항목을 각각 1순위로 지목**합니다 — **강사 발화의 「실무 중요도 신호」 밀도** 🔴. 시간당 2~3회면 성립, 0.2회면 붕괴합니다. [Ch06 전략 §1](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#1-세-개의-질문-하나의-자산)이 명시하듯 **이 신호가 없으면 A·B·C 전부, 그리고 §4 기관 전략까지 동시에 무너집니다.** 실측 전까지 B안은 "가장 유력한 가설"이지 확정된 가치목표가 아닙니다.

### 9. 최종 가치목표 제안
**유지, 단 §7 신호 밀도 실측을 가치목표 확정의 선행 조건으로 명시.** "강사 발화 신호가 시간당 2회 이상"이 확인되면 B안이 콕집의 **코어 가치목표**가 되고, 확인되지 않으면 ①(채용공고) 비중을 올려 문구를 "현직자가 말한 것"에서 "채용 시장이 요구하는 것"으로 바꿔야 합니다([Ch04 딥리서치 §4-2](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#4-2-확정--강사-발화로-출발선을-취업-이력으로-벽을) 참조).

---

## 3. C안 「결과」

### 1. 기존 가치목표
"이 과정을 먼저 마치고 취업한 사람들이 실제로 붙잡았던 것부터 보여드립니다. 당신은 그 순서만 따라가면 됩니다."

### 2. 현재 유효성
**수정(하향) — 현재 시점 가치목표에서 제외, 12개월 뒤 재평가 대상으로 명확히 격하.** Ch08 시점에는 "오늘은 쓸 수 없는 문장"이라는 시점 문제만 지적됐지만, **부록 A의 판정이 이 결론을 훨씬 강하게 뒷받침**합니다.

### 3. 고객 Pain과의 연결
직접적으로는 **PP-K7**(재계약 결정 요인, [Ch06 §4-2](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-pain-list.md#4-2-박성호-지불자--8건--3건)) — 단 `I=S=3`이라 DOS 지표상으로는 **0.00**([Ch06 전략 §4-2 ①](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#4-2-계약-설계-시점에-심어야-하는-두-가지)), "지표에 안 보이나 재계약을 결정한다"는 정성적 근거만 있습니다.

### 4. Desired Outcome
기관의 진짜 Desired Outcome은 **취업률 방어와 예산 정당화**([Ch06 §2-1](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-pain-list.md#2-1-페르소나별-goal--importance를-매길-기준선) 박성호 Goal)이고, 학습자의 진짜 Desired Outcome은 "합격"입니다. C안이 파는 "결과 라벨"은 이 둘 다에게 **수단**이지 목표가 아닙니다 — 이 점은 A안과 같은 구조적 약점입니다.

### 5. 경쟁사·대체재 대비 차별성
가장 방어력이 높은 축입니다. [Ch04 딥리서치 §4-1](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#4-1-판정-근거-후보-4개의-비교) — "다글로가 살 수도 만들 수도 없는 유일한 자산"(방어력·설명력 최고). 문제는 차별성이 아니라 **도달 가능성**입니다.

### 6. AI에 의해 대체될 가능성
**여기가 이번 재검토에서 가장 크게 바뀐 지점입니다.** C안의 메커니즘("과정·결과 기록 → 제3자가 인정 → 신뢰 자산화")은 부록 A가 정확히 같은 구조로 탐침한 **「AI 활용 역량의 증명」 시장**과 겹칩니다. 부록 A-6의 종합 판정은 **수정(Revise)** — [5개 관문 중 5개가 막힘](../appendix-a-post-ai-learner-pain/verdict-ai-competency-proof-market.md#1-중요하다와-돈을-낼-필요가-있다를-가르는-5문) 🟢:

| 관문 | C안에 옮기면 |
|---|---|
| Q1 이미 쓰는 수단으로 해결되는가 | 인턴·라이브코딩 등으로 부분 해결 중 → **막힘** |
| Q2 회피 가능한가 | 기업은 경력직 채용으로 회피 가능(경력 74% vs 신입 26%) 🟢 → **막힘** |
| Q3 내재화가 쉬운가 | 무신사가 자체 전형 설계·집행 실증 🟢 → **막힘** |
| Q5 고통과 지불이 같은가 | 고통은 학습자, 지불 능력은 기업/기관 → **분리** |

추가로 **엑셀화 위험**([부록 A-6 §5-2](../appendix-a-post-ai-learner-pain/verdict-ai-competency-proof-market.md#5-2-️-불리한-방향--엑셀화)) — AI 활용이 보편화되면 "무엇을 붙잡았는가"류 변별 축 자체가 3~5년 내 소멸할 수 있다는 반론이 🟡로 남아 있습니다.

### 7. 이를 뒷받침하는 직접 근거
- 부록 A-6 5관문 판정 🟢([verdict §1](../appendix-a-post-ai-learner-pain/verdict-ai-competency-proof-market.md#1-중요하다와-돈을-낼-필요가-있다를-가르는-5문))
- 딥리서치 §4-1 — 첫 라벨 9~12개월 뒤, 차수당 13명 🟡([kokjip-research.md §4-1](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#4-1-판정-근거-후보-4개의-비교))
- Ch04 딥리서치 §3-3 — 채용 연계 이해상충 🔴([kokjip-research.md §3-3](../04-tam-sam-som-market-segment-map/deep-research/kokjip-research.md#3-3-다만-이-값에는-세-개의-함정이-있습니다))

### 8. 근거가 충분하지 않은 부분
- 부록 A-6의 5관문 판정은 **"AI 활용 역량 증명"이라는 다른 트랙**에서 나온 것이라, 콕집의 C안("결과를 보여주는 것"까지만, 매칭은 하지 않음)에 **그대로 1:1 적용되는지는 검증되지 않았습니다** 🔴 — C안은 부록 A가 지적한 Q5(이해상충)의 상당 부분을 "보여주기까지"로 스스로 제한해 회피하려 하지만, 그 자기 제한이 실제로 유지되는지는 별개 문제입니다.
- 표본 크기(차수당 13명)로 몇 년 안에 통계적 유의성을 갖는지 미검증 🔴.

### 9. 최종 가치목표 제안
**현재 Value Proposition에서 제외.** 폐기는 아닙니다 — 데이터 자산으로서의 적립(로그 수집)은 지금부터 시작하되, **가치목표로 문장화하는 것은 최소 9~12개월 뒤, 그리고 부록 A 실험 D(엑셀화 타이밍)의 결과를 함께 확인한 뒤로 미룹니다.** 지금 이 문장을 앞세우면 도달 불가능한 약속이 됩니다.

---

## 4. 발전 가능성이 있는 항목 — Pain에서 가치목표 후보로

기존 3안 밖에서, **PP-K1**(기관, "취업률이 떨어졌는데 원인을 모른다", 62.6%→54.2% 🟢 실측, AOS 3.00 공동 1위)이 [Ch06 전략 §4](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#4-기관-공략--학습-도구가-아니라-조기-경보)에서 "학습 도구가 아니라 **차수 중 조기 경보**"로 재정의됐습니다. 이것은 A/B/C와 다른 축(개인 대상 메시지가 아니라 **기관 대상 상품 형태**)이며, 경쟁 8곳 중 "차수 중 조기 경보"를 파는 곳이 없다는 점에서([Ch08 §2-3](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#2-3-규모모델-한눈에-대조)) B안과 같은 급의 근거를 갖고 있습니다. **다만 이것은 개인 대상 Value Proposition이 아니라 B2B 상품 라인이므로, 이번 문서의 3안과 같은 층위에서 다루지 않고 별도 트랙으로 표시만 해둡니다.**

---

## 5. 종합 — 현재 KOKJIP Value Proposition

### 5-1. 세 안의 최종 위상

| 안 | 판정 | 위상 |
|---|---|---|
| **A. 시간** | 수정 | 독립 가치목표 아님 — **B의 진입 화법**으로만 사용 |
| **B. 출처** | 유지(조건부) | **코어 가치목표** — 단 신호 밀도 실측([Ch06 §7-①](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#지금-확인할-것--싸고-크게-바꾸는-두-가지))이 선행돼야 확정 |
| **C. 결과** | 수정(보류) | **현재 VP에서 제외** — 9~12개월 뒤 재평가, 로그는 지금부터 적립 |

### 5-2. 한 문장 제안

> **콕집은 무엇을 봐야 할지를 AI가 임의로 판단하지 않고, 강의 중 강사가 실무 중요도를 직접 언급한 순간을 근거로 삼아, 학습자가 가진 남은 시간 안에서 가장 먼저 볼 것만 짚어주는 학습 우선순위 서비스다.**

이 문장은 B(근거) + A(전달 형식)만 담습니다. **C는 의도적으로 빠져 있습니다** — 지금 이 문장에 취업 성과·결과를 넣으면 부록 A-6이 확인한 5관문 문제를 그대로 상속하게 됩니다.

### 5-3. VPS 작성용 정리표

| 요소 | 확정 여부 | 내용 | 선행 조건 |
|---|---|---|---|
| **핵심 가치(Value)** | 조건부 확정 | AI가 아니라 강사 발화가 판정 근거 | 신호 밀도 시간당 2회 이상([Ch06 §7-①](../06-market-opportunity-score/case-01-kokjip-lecture-review-prioritizer-strategy.md#지금-확인할-것--싸고-크게-바꾸는-두-가지)) |
| **전달 프레임(Framing)** | 확정 | 뺄셈의 목적어는 「강의」가 아니라 「학습자의 시간」([Ch08 §6-5](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#6-5-그러나-뺄셈을-버릴-필요는-없다--뺄셈의-목적어를-바꾸면-된다)) | 없음 |
| **금지 표현** | 확정 | "강의에서 버릴 것을 골라준다" · "취업까지 책임진다" · "AI가 퀴즈·학습자료를 만들어준다" | — |
| **보류 요소(C안)** | 보류 | 취업 성공자 학습 이력 기반 결과 제시 | 9~12개월 데이터 적립 + 부록 A 실험 D(엑셀화 타이밍) 결과 |
| **청중별 발화 분리** | 확정 | 학습자="시간 안에 붙잡을 것" / 기관="취업률 방어" / 강사="당신 발화가 근거" ([Ch08 §6-5](./case-01-kokjip-lecture-review-prioritizer-competitor-briefing.md#6-5-그러나-뺄셈을-버릴-필요는-없다--뺄셈의-목적어를-바꾸면-된다)) | — |
| **별도 트랙(참고)** | 확정 | 기관 조기 경보(PP-K1)는 B2C VP와 별개의 B2B 상품 문구 | §4 |

### 5-4. 이 판정이 무너지는 조건

| 조건 | 결과 |
|---|---|
| 강사 발화 신호 밀도가 시간당 0.2회 수준으로 낮게 나옴 | **B안 붕괴.** ①(채용공고) 중심으로 전면 재작성 필요 — VP 문장 자체가 무효 |
| A안의 "남은 시간 입력"에서 학습자 이탈률이 높음 | A는 진입 화법에서도 탈락, PP-3 접근 방식을 다시 설계 |
| 부록 A 실험 D에서 엑셀화 신호(점수 분포 상향)가 조기에 관측됨 | C안은 12개월 뒤에도 승격 불가 — 완전 폐기 검토 |

**세 조건 모두 아직 검증되지 않았습니다.** 이 문서의 결론은 확정이 아니라 **현재까지의 근거로 도달 가능한 가장 정직한 위치**입니다.
