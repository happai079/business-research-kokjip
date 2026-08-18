---
type: schema
title: 원본 루트 등록부
updated: 2026-08-18
---
# 원본 루트 등록부

**위키가 읽는 원본이 어디 있는지의 정본 목록.** 새 원본 루트가 추가되면 여기에 등록한다.

## 등록된 루트

| 루트 | 성격 | 문서 수 | 위키 대응 |
|---|---|:-:|---|
| `00-baseline-research/` | 기준 리서치 SSOT | 2 | [[src-00-integrated-baseline-research]] |
| `01-porters-five-forces/` | 프레임워크 챕터 | 5 | [[five-forces]] |
| `02-value-chain/` | 프레임워크 챕터 | 5 | [[value-chain]] |
| `03-ksf/` | 프레임워크 챕터 | 3 | [[ksf-new-entrant]] |
| `04-tam-sam-som-market-segment-map/` | 프레임워크 챕터 + 딥리서치 | 6 | [[market-sizing]] |
| `05-persona-spectrum-journey-map/` | 프레임워크 챕터 | 5 | [[persona-spectrum]] |
| `06-market-opportunity-score/` | 프레임워크 챕터 | 7 | [[opportunity-score]] |
| `07-jtbd/` | 프레임워크 챕터 | 4 | [[jtbd]] |
| `08-competitor-value-declaration/` | 경쟁 실사 + VPS 산출물 | 6 | [[vps-v2-0-rooted]] |
| `appendix-a-post-ai-learner-pain/` | **병렬 트랙** | 8 | [[post-ai-learner-pain-hub]] |
| `README.md` (루트) | 저장소 진입점 | 1 | [[src-root-readme]] |
| `llm-wiki/raw/` | **외부 신규 원본 유입 지점** | 0 | (비어 있음) |

**합계 52건** → 전수 목록 [[by-source]]

## 세 가지 규칙

### 1. 원본은 복사하지 않는다
챕터 문서는 제자리에 두고 위키가 **상대 경로로 참조**한다. 복사본은 곧 두 개의 진실이 된다.

### 2. 원본은 수정하지 않는다
어떤 이유로도. 원본 쪽 개선 제안은 [[lint-2026-08-18]] §E에 기록하고 **사용자가 판단한다.**

### 3. 새 원본은 `raw/`로 들어온다
리포 루트의 챕터 디렉터리는 **사용자가 저술하는 산출물**이고, `llm-wiki/raw/`는 **외부에서 유입되는 원본**이다. 둘을 섞지 않는다.

| `raw/` 하위 | 무엇이 들어오는가 |
|---|---|
| `deep-research/` | 새 딥리서치 산출물 |
| `market-data/` | 통계·시장 데이터 원본 |
| `competitor-material/` | 경쟁사 약관·공시·화면 캡처 |
| `interviews/` · `transcripts/` | **실제** 인터뷰·녹취 (모의 아님) |
| `articles/` · `papers/` · `reports/` | 기사·논문·보고서 |
| `regulations/` | 법령·고시·훈련기관 규정 |
| `datasets/` · `notes/` · `assets/` | 데이터·자필 노트·이미지 |

## 규모 정책
한 폴더가 **150건을 넘으면 연도(`2026/`)로 분할**한다. 현재는 분할 불필요.

## 연결
[[index]] · [[by-source]] · [[id-system]]
