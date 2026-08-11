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
├── 04-tam-sam-som-market-segment-map/
│   ├── methodology.md                                                 # 방법론 (3층 정의 + 산정 3방식 + 세그먼트 맵 작성법)
│   ├── case-01-kokjip-lecture-review-prioritizer.md                   # 사례: 「콕집」 시장 규모 산정 + 세그먼트 맵
│   └── deep-research/                                                 # 산정 근거 · 간이 리서치
│       ├── methodology.md                                             # 딥 리서치 7단계 방법론
│       ├── kokjip-sizing-evidence.md                                  # 산정 근거: 원천 데이터 · 계산 재현 · 민감도
│       └── kokjip-research.md                                         # 간이 딥 리서치: 경쟁 실사 · 채용 연계 단가
├── 05-persona-spectrum-journey-map/
│   ├── methodology-journey-map.md                                     # 방법론: 고객 여정지도 (단계 도출 4신호 + 레인 6개 + 재사용성 판정)
│   ├── case-01-kokjip-lecture-review-prioritizer-personas.md          # 01-A 기본 페르소나 6종 (사용·지불·영향 역할)
│   ├── case-01-kokjip-lecture-review-prioritizer-persona-spectrum.md  # 01-B 페르소나 스펙트럼 ①단계: 원본 12종
│   └── case-01-kokjip-lecture-review-prioritizer-journey-map.md       # 01-C 유형별 여정지도 + 지불자(기관) 여정
├── 06-market-opportunity-score/
│   ├── methodology.md                                                 # 방법론: 기회점수 (OS→AOS 수식 교정 + 사분면 Matrix + 산출 5단계)
│   ├── methodology-dos.md                                             # 방법론(확장): DOS 시장 가중형 기회점수 (Market Relevance 산정 + AOS×DOS 처분)
│   ├── case-01-kokjip-lecture-review-prioritizer-pain-list.md         # ①단계: CJM에서 추린 대표 Pain 15건 + Goal + 순위/게이트 트랙
│   ├── case-01-kokjip-lecture-review-prioritizer-aos-matrix.md        # ②~⑤단계: Importance·Satisfaction 채점 + AOS 산출 + 중앙값 기준 Matrix
│   ├── case-01-kokjip-lecture-review-prioritizer-dos.md               # ⑥단계: DOS 산출 — SAM 기준(주) · SOM 기준(대조) 두 버전
│   └── case-01-kokjip-lecture-review-prioritizer-strategy.md          # ⑦ 전략 함의: 인식 격차 사슬 · 과금 시점 이동 · 기관 우선 순서
└── 07-jtbd/
    ├── methodology.md                                                 # 방법론: 전환 행동 기반 인터뷰 (모집 3그룹 + 질문 전략 + 4대 동인 + Job Statement)
    ├── case-01-kokjip-lecture-review-prioritizer-interview-guide.md   # ①~③단계: 대상 7명 + 스크리너 + 데모 정의 + 공통 32문 + 페르소나별 문항지
    └── case-01-kokjip-lecture-review-prioritizer-interview-transcripts.md  # ④~⑥단계: ⚫모의 응답 7인 전문 + 4대 동인 채집표 + Job Statement 19문
```

**챕터 07의 응답지는 ⚫ 모의(simulated)입니다.** 실제 인터뷰가 아니라 페르소나 카드에서 역산한 가상 응답이며, 용도는 **문항지 리허설·분석 파이프라인 시험**입니다. 근거로 쓰지 않습니다 → [응답지 머리말](./07-jtbd/case-01-kokjip-lecture-review-prioritizer-interview-transcripts.md#-이-문서의-근거-등급--먼저-읽어야-하는-것)

**딥 리서치는 챕터 폴더 아래에 둡니다.** 04의 산정 근거와 간이 리서치가 `04-.../deep-research/`에 있습니다.

챕터 01의 두 시장을 챕터 02에서도 같은 대상으로 이어 분석했습니다. 01은 산업(외부) 구조를, 02는 기업(내부) 활동을 보므로 두 챕터를 함께 읽어야 "어디서 싸울지"와 "어떻게 싸울지"가 연결됩니다.

## 분석 대상 서비스

챕터 04부터는 **「콕집」** 을 분석 대상으로 삼습니다 — 국비 교육 수강생을 위한, **현직자 인사이트로 복습 우선순위를 정해주는 앱**입니다. 챕터 01~03이 분석한 **산업(에듀테크·AI 교육)** 안에서 **학습자 측에 서는 도구**이며, 산정 결과는 TAM 110~160억 · SAM 200억 · SOM 9.5억입니다 → [Ch04 사례](./04-tam-sam-som-market-segment-map/case-01-kokjip-lecture-review-prioritizer.md)

## 참고

각 챕터는 개념 정리 → 템플릿 작성 → 사례 적용 순으로 진행합니다.
