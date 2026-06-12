# Attached Spec Summary — 의료 AI 진단보조 PoC Mutual NDA

Source: NDA_04_의료PoC_상호NDA.docx (1 page)
Date read: 2026-06-12

## Document Snapshot
- Title: 연구협력 비밀유지계약서 (AI 진단보조 PoC — 상호 NDA)
- Parties: 의료법인 한라병원의료재단 (병원) ↔ 주식회사 메디테크솔루션 (수임자)
- Scope: 흉부 CT 영상 기반 AI 진단보조 PoC 수행을 위한 상호 NDA
- Data Type: 환자 의료데이터 포함 (병원 익명화 후 제공)

## Key Clauses Extracted
- Purpose: 본 연구(PoC) 수행 목적
- Confidential Information: 환자 의료데이터, 임상 프로토콜, 기술 사양, 모델 구조·가중치, 사업 계획 등 포함
- Exceptions: 4대 표준 예외(공지/기존보유/제3자 적법취득/법적의무)만 명시 — 독자개발 예외 부재
- Security: "합리적인 수준"의 보안조치. 클라우드 처리, 처리 위치(국가)는 별도 협의
- IP Ownership: 연구 결과물(모델/가중치/데이터셋/평가결과) 공동 보유
- Subcontracting: CRO/클라우드/보안기관 등 재위탁 허용
- Insurance: 적절한 보험에 가입할 수 있다(임의)
- Term: 계약 효력은 연구 종료 시까지, 비밀유지의무는 종료 후 3년 존속
- Return/Destruction: 종료 또는 병원 요청 시 30일 이내 반환/파기 + 서면 확인
- Governing Law/Jurisdiction: 대한민국법, 서울중앙지방법원 전속 관할

## Implementation-Oriented Change Points for the Skill
- Security Baseline (DR03): "합리적인 수준"을 구체 기준으로 보강 필요 — ISMS-P 또는 ISO/IEC 27001/27701, 저장/전송 암호화(AES-256, TLS1.2+), RBAC/MFA, 망분리 또는 동급, 감사로그 ≥1년, 의료데이터 역식별 금지 및 테스트/개발 환경 반출 금지.
- Cross-Border (DR04): "처리 위치(국가)는 별도 협의" → 국외 이전 시 PIPA Art. 28-8 요건(고지·동의, 적정성, 보호조치 약정) 명시, 계약서에 구체 리전/국가 표기 권장.
- DPA Reference (DR01): 별도 개인정보 처리 위·수탁 계약(PIPA Art. 26) 필수로 명확화.
- Exceptions (R02): 4대 예외 외 "독자개발(Independently Developed)" 예외 추가 필요.
- Purpose Narrowing (R08): 구체적 목적 예시에 "의료 AI 진단보조 PoC 수행" 추가.
- Breach Notification (DR05): "지체 없이" 대신 72시간 내 서면 통지 + 1차 보고서 기준 제시.
- IP Ownership (DR06): 공동 보유는 상업화 장애 → 모델/기술 IP는 기술 제공자 단독 + 데이터 제공자에 대한 비독점 무상 라이선스 권장.
- Subcontractors (DR07): 재위탁 시 책임 승계 및 동등 이상의 비밀유지 의무 명시.
- Insurance (DR08): 임의 규정 → 데이터보호 책임보험 가입 의무화 권장.

## Conformance Assessment vs Market Baseline
- Confidentiality Period: 종료 후 3년 — 시장 표준과 합치(별도 영업비밀 무기한 규정은 문맥상 필요 시 별도 제시 권장).
- Return/Deletion: 30일 + 서면 확인 — 양호.
- Governing Law/Jurisdiction: 대한민국법 + 서울중앙지법 — 우선 선호와 일치.

End of summary.