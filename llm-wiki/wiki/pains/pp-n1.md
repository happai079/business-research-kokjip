---
id: PP-N1
type: pain
title: 내 강의 자산이 외부로 나가지 않게 통제하고 싶다
grade: mixed
persona: [N1]
track: gate
case: case-01-kokjip
updated: 2026-08-18
tags: [gate, p0, data-governance]
---
# PP-N1 — 강의 데이터 유출·저작권 우려

**게이트 Pain이지만 P0 기능을 만들어낸 유일한 항목.**

## 현재 방어책
데이터 보관·삭제 정책이 없어 불안 → **강의 녹음 전면 금지가 유일한 방어책**.

## 해결 설계 (P0 · MVP 필수)
1. **전사 완료 즉시 원본 오디오 휘발성 삭제** ([[tiro]] 모델 🟢)
2. **AI 모델 학습 미사용** 명문화
3. Q&A 구간 **비강사 음성 미저장·비식별화** ([[otter-ai]] 집단소송 선제 방어 🟢)
4. 녹화물 **IP·실연권 강사 귀속** (UMass 표준 🟢)

## 이 Pain이 증명한 것
**Non-user가 P0 기능 목록을 바꿨다.** 이 사람은 콕집을 절대 쓰지 않지만, 이 사람의 저항을 해소하지 못하면 [[c1-kim-jiwon]]에게 도달할 원재료 자체가 없다 🟡.

## 연결
[[gate-pains]] · [[n1-mun-jihun]] · [[data-governance-baseline]] · [[recording-consent-patterns]]
