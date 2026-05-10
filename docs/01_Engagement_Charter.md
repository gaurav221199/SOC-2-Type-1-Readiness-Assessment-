*Engagement Charter — SOC 2 Type 1 Readiness | MeridianHealth Analytics*

**ENGAGEMENT CHARTER**

SOC 2 Type 1 Readiness Assessment

*MeridianHealth Analytics Pty Ltd*

Engagement: MHA-SOC2-2026-001

|**Document Title**|Engagement Charter — SOC 2 Type 1 Readiness Assessment|
| :- | :- |
|**Version**|1\.0|
|**Status**|Final — for sign-off|
|**Date Issued**|3 March 2026|
|**Prepared By**|Gaurav Govind, GRC Analyst|
|**Client Sponsor**|XYZ, Chief Information Security Officer|
|**Classification**|Confidential — Client|

*PORTFOLIO ARTEFACT — All persons and the client entity referenced herein are fictional. Produced for portfolio demonstration purposes.*



**1. Engagement Overview**

MeridianHealth Analytics Pty Ltd (“MeridianHealth”, “the Client”) has engaged the practitioner to perform a SOC 2 Type 1 Readiness Assessment against the AICPA Trust Services Criteria. The assessment will evaluate the design of internal controls supporting the Security Trust Services Category (Common Criteria CC1–CC9) and produce audit-grade artefacts to position MeridianHealth for a successful Type 1 examination by an independent CPA firm.

This Charter defines the scope, deliverables, timeline, governance, and acceptance criteria for the engagement. Both parties agree to the terms set out in this document.

**2. Background & Drivers**

- MeridianHealth holds an active ISO/IEC 27001:2022 certification (issued November 2024, valid through November 2027) covering its Sydney and Melbourne offices and AWS production environments.
- In January 2026, MeridianHealth signed two new US healthcare insurance clients — BlueRidge Health Plan (Oregon) and Cascadia Health (Washington) — whose Master Services Agreements require delivery of a SOC 2 Type 1 report within six months of contract execution.
- Combined annualised revenue from the two US contracts is AUD 4.2 million, with material upside if MeridianHealth can extend into US payer markets.
- MeridianHealth has no prior SOC 2 experience and limited internal capacity to interpret AICPA Trust Services Criteria, prepare control descriptions, or coordinate auditor fieldwork.

**3. Engagement Objectives**

- Assess the design of MeridianHealth’s controls against the AICPA Trust Services Criteria — Security (Common Criteria CC1–CC9) and revised 2022 points of focus.
- Identify control design gaps, missing evidence, and areas where existing ISO 27001 controls require strengthening or supplementation for SOC 2.
- Produce an ISO 27001:2022 ↔ SOC 2 Security TSC crosswalk to maximise reuse of existing control work and minimise duplication of effort.
- Deliver a prioritised remediation roadmap with owners, target dates, and effort estimates sufficient to position MeridianHealth for Type 1 audit readiness within 90 days post-engagement.
- Produce Board-ready artefacts (Executive Summary and Risk Scorecard) for the MeridianHealth Audit and Risk Committee.

**4. Scope**
## **4.1 In Scope**
- Trust Services Criterion: Security (mandatory Common Criteria CC1 through CC9).
- System boundary: MeridianHealth Analytics Platform (production environment) hosted on AWS ap-southeast-2 (Sydney) and us-east-1 (N. Virginia).
- Supporting infrastructure: Okta (SSO/MFA), AWS IAM Identity Center, GitHub Enterprise, Jira, Confluence, ServiceNow, BambooHR, Datadog, AWS GuardDuty, AWS Security Hub, CrowdStrike Falcon, Jamf, and Microsoft Intune.
- Personnel: All 87 MeridianHealth employees and contractors with logical or physical access to the production environment.
- Locations: Sydney head office (Level 14, 2 Bligh Street) and Melbourne office (Level 8, 271 Collins Street).
## **4.2 Out of Scope**
- Trust Services Criteria for Availability, Processing Integrity, and Privacy (deferred to a future Type 2 engagement).
- Confidentiality criterion (recommended for inclusion in Type 2 engagement; assessed at high level only in this Type 1).
- Field testing of operating effectiveness over a period (Type 2 activity — not part of Type 1).
- Penetration testing, red-team exercises, or vulnerability scanning (separate procurement, may be referenced as supporting evidence).
- Sub-service organisations carved-out of the system boundary (AWS, Okta, Datadog) — reliance will be placed on their published SOC 2 reports.

**5. Deliverables**

|**#**|**Deliverable**|**Description**|
| :- | :- | :- |
|D1|**Engagement Charter**|This document. Scope, deliverables, timeline, governance, sign-off.|
|D2|**Control Matrix Workbook**|65 controls across CC1–CC9 with status, evidence, owner, residual risk rating.|
|D3|**ISO 27001 ↔ SOC 2 Crosswalk**|ISO 27001:2022 Annex A controls mapped to SOC 2 Security TSC points of focus.|
|D4|**Findings Register & Remediation Roadmap**|Prioritised findings with severity, owner, target date, and remediation effort.|
|D5|**Policy Pack**|Five core policies: InfoSec, Access Control, Incident Response, Change Management, Vendor Management.|
|D6|**Readiness Assessment Report**|Full assessment narrative: scope, methodology, findings, recommendations.|
|D7|**Executive Summary**|Two-page Board-ready summary for CEO and Audit Committee.|
|D8|**Risk Scorecard**|One-page risk dashboard with heatmap and KPIs.|

**6. Engagement Timeline**

The engagement runs across eight weeks, structured into four phases:

|**Phase**|**Weeks**|**Activities**|**Key Outputs**|
| :- | :- | :- | :- |
|**Phase 1 — Mobilisation**|W1|Kick-off, stakeholder identification, system description drafting, document request list issued.|Engagement Charter signed; system description draft v1.|
|**Phase 2 — Assessment**|W2–W5|Control walkthroughs, evidence inspection, ISO 27001 crosswalk, control rating, gap identification.|Control Matrix v1; ISO crosswalk; preliminary findings list.|
|**Phase 3 — Findings & Remediation**|W6–W7|Findings validation, remediation planning, policy gap drafting, management response collection.|Findings Register; Roadmap; Policy Pack drafts.|
|**Phase 4 — Reporting**|W8|Final report, Executive Summary, Risk Scorecard, walkthrough with CEO and Audit Committee.|All deliverables D1–D8 finalised and signed off.|

**7. RACI Matrix**

Roles: R = Responsible (does the work); A = Accountable (signs off); C = Consulted (input sought); I = Informed.

|**Workstream**|**Practitioner**|**CISO**|**CTO**|**CEO**|**Audit Cmte**|
| :- | :- | :- | :- | :- | :- |
|**Engagement Charter sign-off**|R|A|C|I|I|
|**System description**|R|A|C|I|I|
|**Control walkthroughs & rating**|R|A|C|I|I|
|**ISO 27001 crosswalk**|R|A|I|I|I|
|**Findings validation**|R|A|C|I|I|
|**Remediation roadmap approval**|C|R|A|I|C|
|**Policy Pack drafting**|R|A|C|I|I|
|**Executive Summary & Scorecard**|R|C|C|A|I|
|**Auditor selection (downstream)**|C|R|C|A|C|

**8. Assumptions & Dependencies**

- Existing ISO 27001:2022 ISMS documentation is current and accurately reflects operating practice.
- Control owners are available for scheduled walkthroughs (allowance: 2–3 hours per owner).
- Evidence is provided through ServiceNow, Confluence, GitHub, AWS, and Okta consoles within agreed turnaround times (5 business days).
- Sub-service organisations (AWS, Okta, Datadog) maintain current SOC 2 Type 2 reports made available to MeridianHealth.
- MeridianHealth will engage an independent licensed CPA firm separately for the Type 1 examination; auditor selection is not within this engagement’s scope.
- No material organisational restructure, M&A activity, or production environment migration occurs during the engagement period.

**9. Acceptance Criteria**

- All eight deliverables (D1–D8) are delivered by the engagement end date.
- The Control Matrix covers a minimum of 60 controls across all nine Common Criteria categories.
- Findings are categorised by severity (High / Medium / Low) with documented residual risk rationale.
- The remediation roadmap defines actions sufficient to achieve audit readiness within 90 days of engagement close.
- All deliverables are reviewed by the CISO and accepted in writing by the Client Sponsor.

**10. Risks to the Engagement**

|**Risk**|**Likelihood**|**Mitigation**|
| :- | :- | :- |
|Control owners unavailable for walkthroughs|Medium|CISO to confirm walkthrough calendar in W1; escalation path to CTO documented.|
|Evidence quality below threshold (verbal-only or stale)|High|Evidence Reliability rating (A/B/C) applied per control; C-rated evidence flagged in Findings Register for remediation.|
|Scope creep into Confidentiality, Availability TSC|Medium|Charter-defined scope; change requests handled via written variation only.|
|Disagreement between practitioner and management on findings severity|Low|Findings reviewed in W7; management response documented alongside finding regardless of agreement.|

**11. Sign-Off**

By signing below, both parties agree to the scope, deliverables, timeline, and governance defined in this Engagement Charter.
**\


|**Practitioner**|**Client Sponsor**|
| :- | :- |
|Name: Gaurav Govind|Name: XYZ|
|Role: GRC Analyst|Role: Chief Information Security Officer|
|Signature: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_|Signature: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_|
|Date: 3 March 2026|Date: \_\_\_\_\_\_\_\_\_\_\_|

** 

*PORTFOLIO ARTEFACT — Signatures are illustrative. This engagement is simulated for portfolio demonstration purposes.*
Confidential — Client | Page  of 
