---
type: schema
title: 페이지 계약 — 유형별 필수 구성
updated: 2026-08-18
---
# 페이지 계약

운영 계약 본문은 [AGENTS.md](../../AGENTS.md). 이 문서는 **유형별로 무엇이 반드시 있어야 하는가**만 규정한다.

## 모든 페이지 공통

1. **YAML 프론트매터** — `type` 필수. 나머지는 유형별.
2. **H1 제목** — 파일명이 아니라 사람이 읽는 제목.
3. **한 줄 요지** 또는 그에 준하는 첫 단락.
4. **`## 연결` 섹션** — 최소 1개의 위키링크. 없으면 고아 페이지다.
5. **등급 표기** — 사실 주장이 있는 모든 문장에 🟢🟡🔴⚪ 중 하나.

## 유형별 추가 요건

| type | 반드시 있어야 하는 것 |
|---|---|
| `source` | `source_path` · `doc_kind` · **`ingest_depth`** (full/partial/outline) · 원본 상대 링크 · "이 문서가 확정한 것" · "미완" |
| `case` | `id` 또는 `case` · 현재 판정 상태 |
| `framework` | 정의 · 콕집 적용 결과 · **원본 방법론의 경고(있으면 반드시 인용)** |
| `entity` | `subtype` · 규모·모델(🟢) · 콕집 관점의 위협 |
| `persona` | `id` · 역할(User/Buyer/Gatekeeper 등) · 소유한 Pain |
| `pain` | `id` · `track`(rank/gate) · 점수(rank일 때) · 현재 대체 수단과 한계 · 요구하는 제품 결정 |
| `claim` | `id` · `status` · **무너지면 무엇이 무너지는가** · 검증 설계(방법·기간·임계값) |
| `contradiction` | `id` · `status` · 양쪽 주장 · **현재 처분과 그 이유** |
| `metric` | 값 · 등급 · **산출식 또는 출처** |
| `question` | 답이 나오면 **어떤 페이지가 바뀌는지** · 가능하면 임계값 |
| `evidence` | 출처 기관·문서 · 대응 위키 페이지 |

## 금지 패턴

- 등급 없는 수치
- 도출 과정 없는 🟡
- 임계값 없는 🔴
- `## 연결` 없는 페이지
- 원본에 없는 사실의 창작 (추론이면 🟡로 표기하고 과정을 남긴다)

## 인용 시 특별 주의가 필요한 원본

| 원본 | 주의 |
|---|---|
| [[src-07-case-interview-transcripts]] | **166KB 전부 모의 데이터.** 인용 시 "모의" 병기 필수 |
| [[src-08-vps-v1-0-merged]] 등 v1.0 3종 | **대체됨.** 현행은 [[vps-v2-0-rooted]] |
| [[src-apx-ai-substitutability]] · [[src-apx-opportunity-map]] | 부록 A는 **1차 인터뷰 0건**. 강도·빈도·지불 의사 미확인 |

## 연결
[[id-system]] · [[evidence-grades]] · [[index]] · [[source-page]]
