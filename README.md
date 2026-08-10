# business-research-practice

산업 및 비즈니스 분석 기초 프레임워크 학습 저장소.

시장·고객·경쟁 구조를 분석하는 대표 프레임워크를 챕터별로 학습하고, 실제 사례에 적용한 결과물을 정리합니다.

## 학습 챕터

| # | 챕터 | 다루는 내용 |
|---|---|---|
| 01 | Porter's Five Forces 모델 | 산업 구조와 경쟁 강도를 5가지 힘으로 분해 |
| 02 | 기업 내부 활동의 가치 사슬 분석 | Value Chain 관점에서 내부 활동별 부가가치 진단 |
| 03 | 핵심 성공 요인(KSFs) 분석 | 해당 산업에서 이기기 위한 필수 조건 도출 |
| 04 | TAM-SAM-SOM 과 Market Segment Map | 시장 규모 산정과 세그먼트 지도 작성 |
| 05 | 페르소나, 페르소나 스펙트럼, 고객 여정지도 | 고객을 구체화하고 접점별 경험을 추적 |
| 06 | 시장기회 분석 | 기회점수(OS) 기반 우선순위 판단 |
| 07 | JTBD(Jobs-To-Be-Done) 분석 | 고객 상황을 객관화해 해결할 과업 정의 |

## 진행 흐름

```
산업 구조 파악 (01~03)  →  시장 정의 (04)  →  고객 이해 (05, 07)  →  기회 우선순위 (06)
                 ↕
         딥 리서치 (가정 검증)
```

앞선 챕터의 산출물이 뒤 챕터의 입력이 됩니다. 예를 들어 05의 페르소나는 07의 JTBD 진술문으로, 04의 세그먼트와 07의 과업은 06의 기회점수 계산으로 이어집니다.

프레임워크가 **분석의 틀**이라면 [딥 리서치](./04-tam-sam-som-market-segment-map/deep-research/methodology.md)는 **틀을 채울 사실을 찾아오는 절차**입니다. 각 챕터가 남긴 "검증이 필요한 가정"을 실제 데이터로 바꾸고, 그 결과를 다음 챕터의 입력으로 되돌립니다.

## 구조

```
business-research-practice/
├── README.md
├── 01-porters-five-forces/
│   ├── methodology.md                            # 분석 방법론 원문
│   ├── case-01-ai-education-edtech.md            # 사례: AI AX/DX 교육 에듀테크 산업
│   ├── case-02-autonomous-driving-automotive.md  # 사례: 자율주행 중심 자동차 산업
│   └── comparison-edtech-vs-automotive.md        # 두 시장 비교 분석
├── 02-value-chain/
│   ├── methodology.md                            # 분석 방법론 (도메인 중립 질문표 + 출력 포맷 + 치환 예시)
│   ├── case-01-ai-education-edtech.md            # 사례: AX/DX 교육 사업자의 가치사슬
│   ├── case-02-autonomous-driving-automotive.md  # 사례: 자율주행 완성차 기업의 가치사슬
│   └── comparison-edtech-vs-automotive.md        # 두 기업 가치사슬 비교 분석
├── 03-ksf/
│   ├── new-entrant-top5-ksf.md                   # 신규 진입자를 위한 Top 5 핵심 성공 요인
│   └── ksf-case-evidence.md                      # 각 KSF를 실제 기업 사례로 검증한 사례집
└── 04-tam-sam-som-market-segment-map/
    ├── methodology.md                            # 방법론 (3층 정의 + 산정 3방식 + 세그먼트 맵 작성법)
    ├── case-01-ai-education-edtech.md            # 사례: AX 교육 시장 규모 산정 + 세그먼트 맵
    └── deep-research/                            # 심층 리서치 일체
        ├── methodology.md                        # 딥 리서치 7단계 방법론
        ├── case-ai-ax-edtech.md                  # 본문: AX/DX 교육 산업 리서치 1~7단계
        ├── segment-map.md                        # 세그먼트 지도 (2×2 좌표 · 탈락 깔때기 · 경쟁 밀도)
        ├── srs-ax-adoption-platform.md           # 7단계 제품 명세 (SRS)
        ├── research-log.md                       # 미해소 항목 · 선행 리서치 대조 · 다음 회차 설계
        ├── market-sizing-evidence.md             # 04 산정 근거: 원천 데이터 · 계산 재현 · 민감도
        └── 리서치 원문/                           # 같은 주제의 선행 리서치 (Gemini·GPT)
```

**딥 리서치는 챕터 폴더 아래에 둡니다.** 현재는 04 아래에 모여 있습니다 — 01~03의 가정을 검증한 리서치와 04의 시장 규모 산정 근거가 같은 폴더에 있는데, 전자의 산출물(세그먼트·계정당 단가·미해소 항목)이 그대로 04의 입력이 되기 때문입니다.

챕터 01의 두 시장을 챕터 02에서도 같은 대상으로 이어 분석했습니다. 01은 산업(외부) 구조를, 02는 기업(내부) 활동을 보므로 두 챕터를 함께 읽어야 "어디서 싸울지"와 "어떻게 싸울지"가 연결됩니다.

딥 리서치는 챕터 01~03이 세운 가정을 공개 데이터로 검증한 결과이기도 합니다. 검증 과정에서 챕터 01의 판단 세 가지가 수정됐습니다.

| 챕터 01의 판단 | 리서치 후 |
|---|---|
| 시장이 빠르게 커진다 | 수요는 커졌으나 **교육 예산 총액은 커지지 않았다** (증액 기업 35.8%) |
| B2G 매출 의존은 금지 | **현금은 B2G, 자산은 B2B** — 역할을 분리한다 |
| 기존 경쟁 강도 4/5 (성장에 가려진 강) | **5/5** — AX 영역은 12개 사업자 경쟁에 정부 무료 공급까지 진입 |

챕터 04에서는 앞선 리서치의 수치 해석 하나가 수정됐습니다. **"AI 교육이 2026년 투자 1순위(50.9%)"는 우선순위 응답 비중이지 금액 비중이 아니며**, 금액 기준은 약 25%입니다([근거](./04-tam-sam-som-market-segment-map/deep-research/market-sizing-evidence.md#3-a10ai-교육-금액-비중-25의-유도)).

근거는 [리서치 문서](./04-tam-sam-som-market-segment-map/deep-research/case-ai-ax-edtech.md)의 [경쟁 실사](./04-tam-sam-som-market-segment-map/deep-research/case-ai-ax-edtech.md#5-6-h5-검증--빈-땅이-아니었다)와 [6단계 정제](./04-tam-sam-som-market-segment-map/deep-research/case-ai-ax-edtech.md#6단계--반복-정제)에 있습니다.

## 참고

각 챕터는 개념 정리 → 템플릿 작성 → 사례 적용 순으로 진행합니다.
