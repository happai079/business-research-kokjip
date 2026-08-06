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
```

앞선 챕터의 산출물이 뒤 챕터의 입력이 됩니다. 예를 들어 05의 페르소나는 07의 JTBD 진술문으로, 04의 세그먼트와 07의 과업은 06의 기회점수 계산으로 이어집니다.

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
└── ...          # 챕터별 산출물이 추가되는 대로 정리
```

챕터 01의 두 시장을 챕터 02에서도 같은 대상으로 이어 분석했습니다. 01은 산업(외부) 구조를, 02는 기업(내부) 활동을 보므로 두 챕터를 함께 읽어야 "어디서 싸울지"와 "어떻게 싸울지"가 연결됩니다.

## 참고

각 챕터는 개념 정리 → 템플릿 작성 → 사례 적용 순으로 진행합니다.
