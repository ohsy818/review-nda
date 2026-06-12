# CHANGELOG v2

Date: 2026-06-12

Summary: Update NDA review skill per attached medical AI PoC mutual NDA (NDA_04_의료PoC_상호NDA.docx, 1p).

Key changes:
- DR03 Security: Clarified concrete security baseline (ISMS-P/ISO 27001/27701, AES-256 at rest, TLS 1.2+, RBAC/MFA, network segregation, audit log ≥1y), added medical data handling notes (no re-identification; no test/dev export).
- DR04 Cross-border: Added PIPA Art. 28-8 compliance details and discouraged vague “separately agreed” wording. Require explicit region/country in contract.
- DR01 DPA reference: Fixed statute acronym to PIPA Art. 26.
- R08 Purpose: Added concrete example "의료 AI 진단보조 PoC 수행" for purpose narrowing.
- R02 Exceptions: Softened wording to "자주 누락됨" while keeping the requirement to include the Independently Developed exception.

No changes required but validated against the attached NDA:
- R03 Confidentiality Period: 3 years post-termination acceptable (matches market standard).
- R13 Destruction Certificate + R15 Return/Deletion Deadline: 30 days + written confirmation acceptable.
- R06 Governing Law: Korea law + Seoul Central District Court (preferred default) — aligned.

Domain-specific guidance already present and re-affirmed due to attached NDA contents:
- DR01 Separate DPA required for patient data.
- DR06 IP ownership clarity to avoid joint ownership; advocate split ownership + license-back.
- DR07 Subcontractor liability chain.
- DR05 Breach notification within 72 hours (replace "지체 없이" with a firm timeline).
- DR08 Insurance requirement.

References:
- Source document: NDA_04_의료PoC_상호NDA.docx (1 page) — medical AI diagnostic PoC mutual NDA.