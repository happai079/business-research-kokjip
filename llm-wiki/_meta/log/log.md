---
type: log
title: 위키 작업 로그
updated: 2026-08-18
---
# 로그

추가 전용(append-only). 항목은 `## [YYYY-MM-DD] <작업> | <대상>` 형식으로 시작한다.
빠른 조회: `grep "^## \[" _meta/log/log.md | tail -5`

## [2026-08-18] scaffold | 폴더 트리 v1 (유형 축)
- `_meta`/`raw`/`wiki`/`outputs`/`tools` 5계층, leaf 59곳 `.gitkeep`
- 원본 유형을 확인하지 않은 상태의 일반형 트리였음

## [2026-08-18] scaffold | 폴더 트리 v2 (실제 문서 분류 반영)
- 원본 51건 인벤토리 후 재구성 — 64 dirs
- `raw/`를 딥리서치·시장데이터·경쟁자료·인터뷰·법령 등 실제 유입 유형으로 교체
- `wiki/`에 `cases`·`personas`·`pains`·`jobs`·`claims`·`contradictions`·`evidence`·`metrics` 승격
- `wiki/sources/`를 `in-repo`/`external`로 분리 — **원본을 복사하지 않고 참조하는 결정**을 구조로 고정

## [2026-08-18] schema | 위키 운영 계약 수립
- `AGENTS.md` — 3계층·페이지 유형 19종·링크 규칙 2종·근거 등급 4단계·워크플로 3종(ingest/query/lint)·금지사항 5
- `_meta/taxonomy/id-system.md` — 원본 ID 승계 체계. **`P-*`(부록 Pain)와 `P1~P7`(청년 지표) 충돌 해소 규칙 명시**
- `_meta/taxonomy/evidence-grades.md` — 🟢🟡🔴⚪ 정의 및 승격·강등 규칙
- `_meta/templates/` 5종

## [2026-08-18] ingest | 원본 52건 전수 등재 + 지식 페이지 86개 생성
- **정독 깊이:** full 12 · partial 20 · outline 20 — 각 출처 페이지 frontmatter `ingest_depth`에 기록
- 생성: 지식 페이지 86 — 허브 2 · 케이스 8 · 프레임워크 7 · 엔티티 10 · 페르소나 6 · Pain 15 · 개념 6 · 수치 4 · 주장 7 · 모순 2 · 근거 3 · 비교 4 · 종합 5 · JTBD 2 · 질문 3 · 결정 1 · 연표 1
- **최대 발견:** [[ctr-01-appendix-a-vs-vps]] — 부록 A가 VPS v2.0의 코어 가치 B를 지지하지 않음. **병렬 트랙 유지로 처분**(해소하지 않음)
- **신규 질문 등록:** [[q-01-generic-ai-parity]] — 기존 검증 계획 3건 어디에도 이 질문이 없음
- 인덱스 4종([[index]]·[[by-question]]·[[by-source]]·[[by-status]]) 생성

## [2026-08-18] lint | 1차 점검
- 링크 무결성 검사: 깨진 위키링크 0 · 고아 페이지 0
- 미완 항목 21건 식별 → [[lint-2026-08-18]]
