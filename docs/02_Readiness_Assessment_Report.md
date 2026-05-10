*Readiness Assessment Report — SOC 2 Type 1 | MeridianHealth Analytics*

**SOC 2 TYPE 1**

**READINESS ASSESSMENT REPORT**

*Trust Services Criterion — Security (Common Criteria CC1–CC9)*

*MeridianHealth Analytics Pty Ltd*

Engagement: MHA-SOC2-2026-001

|**Document Title**|SOC 2 Type 1 Readiness Assessment Report|
| :- | :- |
|**Version**|1\.0 — Final|
|**Date Issued**|28 April 2026|
|**Prepared By**|Gaurav Govind, GRC Analyst|
|**Client Sponsor**|XYZ, Chief Information Security Officer|
|**Reporting Period**|Point-in-time as at 28 April 2026 (Type 1)|
|**Classification**|Confidential — Client|

*PORTFOLIO ARTEFACT — Simulated engagement. MeridianHealth Analytics Pty Ltd is fictional. All findings, evidence references, and persons named are illustrative.*



**Contents**



\1. Executive Summary MeridianHealth Analytics Pty Ltd (“MeridianHealth”) engaged the practitioner to perform a SOC 2 Type 1 Readiness Assessment against the AICPA Trust Services Criteria — Security (Common Criteria CC1 through CC9). The engagement objective was to assess the design of MeridianHealth's controls, identify gaps requiring remediation, and produce a roadmap to position MeridianHealth for a successful Type 1 examination by an independent CPA firm. MeridianHealth holds an active ISO/IEC 27001:2022 certification and operates a mature Information Security Management System (ISMS). The engagement made extensive use of existing ISMS artefacts to minimise duplication of effort. The assessment evaluated 65 controls across the nine Common Criteria categories and mapped 93 ISO 27001:2022 Annex A controls to SOC 2 Security TSC criteria.	[9](#_toc)

1.1 Headline Findings	[9](#_toc1)

1.2 Overall Readiness Position	[9](#_toc2)

MeridianHealth's existing ISMS provides a strong foundation for SOC 2 Type 1. The maturity of the ISO 27001 ISMS, combined with modern cloud-native infrastructure and a security-conscious engineering culture, means the gap to SOC 2 Type 1 audit readiness is manageable.	[9](#_toc3)

All four High-severity findings can be closed within the first two-week sprint. With successful execution of the recommended 90-day remediation roadmap, MeridianHealth is on track to achieve Type 1 audit readiness by 28 July 2026, in line with the contractual commitment to BlueRidge Health Plan and Cascadia Health.	[9](#_toc4)

1.3 Key Strengths	[9](#_toc5)

1.4 Key Areas for Action	[10](#_toc6)

\2. Engagement Scope and Approach	[11](#_toc7)

2.1 Objectives	[11](#_toc8)

The engagement was conducted to:	[11](#_toc9)

2.2 In Scope	[11](#_toc10)

2.3 Out of Scope	[11](#_toc11)

2.4 Assessment Approach	[11](#_toc12)

The engagement followed a five-phase approach over an eight-week period:	[11](#_toc13)

\3. System Description	[12](#_toc14)

3.1 Entity Overview	[12](#_toc15)

MeridianHealth Analytics Pty Ltd is a Sydney-based SaaS provider of healthcare analytics dashboards for private health insurers. Founded in 2019, the company operates with 87 personnel across Sydney (62), Melbourne (18), and remote locations across Australia (7).	[12](#_toc16)

The MeridianHealth Analytics Platform ingests claims data from health insurer customers and produces analytics covering fraud detection, utilisation analytics, and member risk scoring. As of April 2026, MeridianHealth serves six Australian private health insurer customers and two newly contracted US health insurance customers (BlueRidge Health Plan and Cascadia Health).	[12](#_toc17)

3.2 Services in Scope	[12](#_toc18)

The MeridianHealth Analytics Platform comprises:	[12](#_toc19)

3.3 Infrastructure	[12](#_toc20)

MeridianHealth operates a fully cloud-native architecture on Amazon Web Services. Production workloads run in ap-southeast-2 (Sydney) for Australian customers and us-east-1 (N. Virginia) for US customers, with logical separation of customer data by region of residence.	[12](#_toc21)

3.4 Sub-Service Organisations (Carved Out)	[12](#_toc22)

The following sub-service organisations are carved out of the system boundary. Reliance is placed on their published independent assurance reports:	[13](#_toc23)

3.5 Personnel	[13](#_toc24)

MeridianHealth's 87 personnel are organised into Engineering (38), Customer Operations (21), Commercial (14), People & Culture (5), Finance (5), and Executive (4). All personnel undergo background checks at hire (per Checkr integration) and annual security awareness training (per KnowBe4).	[13](#_toc25)

\4. Methodology	[14](#_toc26)

4.1 Frameworks Applied	[14](#_toc27)

4.2 Evidence Inspection	[14](#_toc28)

For each of the 65 controls assessed, the practitioner performed at least one of: control owner interview, documentation review, screen-share walkthrough of the operating system or tool, sample evidence extraction, or live observation. Evidence was rated for reliability on a three-tier scale:	[14](#_toc29)

4.3 Control Status Rating	[14](#_toc30)

4.4 Residual Risk Rating	[14](#_toc31)

Each control with a status of Partial or Not Implemented was assigned a residual risk rating reflecting the likelihood of an audit exception and the magnitude of remediation required. Ratings: High, Medium, Low, None.	[14](#_toc32)

\5. Summary of Findings	[15](#_toc33)

5.1 Findings Profile	[15](#_toc34)

Twenty-two findings were raised across the engagement, summarised below:	[15](#_toc35)

5.2 Findings Heatmap by Common Criteria	[15](#_toc36)

The distribution of findings across the nine Common Criteria categories is shown below. CC6 (Logical Access), CC7 (System Operations), and CC9 (Risk Mitigation) account for the majority of findings, consistent with industry patterns for first-time SOC 2 readiness.	[15](#_toc37)

\6. Detailed Findings by Common Criteria This section presents findings by Common Criteria category. Full finding details (description, recommendation, owner, target date, effort) are provided in the separate Findings Register & Roadmap workbook.	[16](#_toc38)

6.1 CC1 — Control Environment	[16](#_toc39)

Two findings were raised. The High-severity finding (F-001) relates to security awareness training completion at 78% (target 100%) and the absence of phishing simulation. SOC 2 audit pattern is full population coverage with retained per-user evidence, supplemented by phishing exercise evidence.	[16](#_toc40)

F-005 (Medium) reflects the absence of a Board-approved Information Security Charter and Risk Appetite Statement. While the Board receives quarterly security updates, formal documentation of Board-level risk appetite is required by the SOC 2 audit pattern.	[16](#_toc41)

6.2 CC2 — Communication and Information	[16](#_toc42)

Two findings were raised. F-002 (High) is the absence of a defined customer incident notification SLA. The current MSA references “reasonable timeframes”, which does not satisfy US healthcare client expectations. A 72-hour SLA aligned with HIPAA breach notification practice is recommended.	[16](#_toc43)

F-006 (Medium) is the absence of a customer-facing Trust Centre. While not a strict SOC 2 requirement, US enterprise customers increasingly expect a public Trust Centre publishing assurance status, sub-processors, and incident commitments.	[16](#_toc44)

6.3 CC3 — Risk Assessment	[16](#_toc45)

F-007 (Medium) reflects the absence of a documented fraud risk assessment. SOC 2 (linked to COSO) expects fraud risk to be considered in the broader risk assessment process, even where not material to the entity.	[16](#_toc46)

6.4 CC4 — Monitoring Activities	[16](#_toc47)

F-008 (Medium) is the absence of an internal audit function independent of management. ISO 27001 surveillance audits provide some independent assurance, but SOC 2 expects a separate internal audit function. Engagement of an external internal-audit provider is recommended.	[16](#_toc48)

6.5 CC5 — Control Activities	[16](#_toc49)

F-009 (Medium) covers four policies (DLP, Cryptography, Mobile Device, Acceptable Use) over 24 months old without review. F-010 (Medium) is the absence of a documented Segregation of Duties matrix; SoD is observed in practice (mandatory peer review on production changes) but not formally documented or reviewed.	[16](#_toc50)

6.6 CC6 — Logical and Physical Access Controls	[16](#_toc51)

Three findings were raised in the most-tested SOC 2 area. F-003 (High) is the most material: user access reviews are performed annually rather than the SOC 2 audit pattern of quarterly reviews with retained manager sign-off.	[17](#_toc52)

F-011 (Medium) is the absence of a Privileged Access Management (PAM) tool for OS-level administrative access. AWS console access is mediated via IAM Identity Center with break-glass; OS-level admin on EC2 instances lacks session recording. F-012 (Medium) is the absence of a service account inventory.	[17](#_toc53)

6.7 CC7 — System Operations	[17](#_toc54)

Four Medium-severity findings were raised. F-013 covers a backlog of 12 High-severity vulnerabilities open beyond their 30-day SLA. F-014 covers an overdue incident response tabletop exercise (last conducted September 2024). F-015 covers the absence of a documented Communications Playbook for incident response. F-016 covers the absence of a recent (within 12 months) full backup recovery test.	[17](#_toc55)

6.8 CC8 — Change Management	[17](#_toc56)

F-017 (Medium) is the only finding in this category: change evidence (GitHub PRs, Jira tickets) is retained for 6 months by default, while SOC 2 fieldwork typically requires 12+ months of change evidence available for sample testing.	[17](#_toc57)

6.9 CC9 — Risk Mitigation	[17](#_toc58)

Five findings were raised. F-004 (High) is the absence of a Complementary User Entity Control (CUEC) tracker for AWS, Okta, and Datadog. SOC 2 fieldwork involves auditor verification that CUECs are mapped and addressed.	[17](#_toc59)

F-018 (Medium) is the absence of a recent BCP test. F-019 (Medium) is an untested cross-region DR failover. F-020 (Medium) covers the absence of continuous vendor monitoring. F-021 (Medium) covers incomplete automation of data retention and deletion.	[17](#_toc60)

\7. Control Coverage Analysis	[18](#_toc61)

7.1 Coverage by Common Criteria Category	[18](#_toc62)

Control coverage was strongest in CC1 (Control Environment, 71% Implemented) and CC6 (Logical Access, 67% Implemented — weighted down by partial PAM and access review findings). Coverage was weakest in CC4 (Monitoring Activities), CC5 (Control Activities), and CC9 (Risk Mitigation), each at 50% Implemented.	[18](#_toc63)

7.2 Evidence Reliability Distribution	[18](#_toc64)

Of the 64 in-scope controls assessed, 26 are supported by A-rated (High reliability) evidence, 27 by B-rated (Moderate) evidence, and 11 by C-rated (Low) evidence. Strengthening C-rated evidence to at least B-rating is a key remediation theme captured in the findings register.	[18](#_toc65)

\8. ISO 27001:2022 Reuse Analysis	[19](#_toc66)

MeridianHealth's existing ISO 27001:2022 ISMS provides a substantial foundation for SOC 2 Type 1. The detailed crosswalk (refer to ISO 27001 ↔ SOC 2 Crosswalk workbook) maps 93 ISO 27001:2022 Annex A controls against the SOC 2 Security TSC points of focus.	[20](#_toc67)

8.1 Reuse Summary	[20](#_toc68)

8.2 Net-New Controls Required	[20](#_toc69)

Twelve SOC 2 Security TSC criteria require net-new controls beyond the existing ISMS. These centre on:	[20](#_toc70)

8.3 Strategic Implication	[20](#_toc71)

The 82.4% direct reuse rate means MeridianHealth can pursue Type 1 readiness primarily through evidence strengthening and process formalisation rather than building new controls. This significantly reduces the net cost and timeline of SOC 2 readiness compared to an entity without an existing ISMS.	[20](#_toc72)

\9. Remediation Roadmap Summary	[21](#_toc73)

A 90-day remediation roadmap, structured into six two-week sprints, has been developed to address all 22 findings. Detailed sprint-by-sprint planning is in the Findings Register & Roadmap workbook.	[22](#_toc74)

9.1 Sprint Overview	[22](#_toc75)

9.2 Resource Requirements	[22](#_toc76)

Total remediation effort is estimated at 155 person-days across 90 days. Effort concentrates in Security Engineering (35 days), CISO office (28 days), and Platform Engineering (16 days). Most findings can be addressed by existing teams without external resourcing; the recommended PAM rollout (F-011) and external internal-audit engagement (F-008) are the two activities with potential procurement implications.	[22](#_toc77)

\10. Recommendations to Management	[23](#_toc78)

10.1 Strategic Recommendations	[23](#_toc79)

Beyond the specific findings, three strategic recommendations support sustainable SOC 2 maturity:	[23](#_toc80)

10.2 Auditor Selection	[23](#_toc81)

The practitioner is independent of the Type 1 audit firm and does not recommend a specific auditor. Selection criteria to consider include: SaaS sector experience, Australian-US dual capability (some auditors specialise in either jurisdiction), pricing model (fixed-fee versus time-and-materials), and ability to co-ordinate with the existing ISO 27001 certification body to minimise duplicative evidence requests.	[23](#_toc82)

10.3 Audit Period Planning	[23](#_toc83)

MeridianHealth should aim for a Type 1 “as-of” date of 31 July 2026, allowing the full 90-day remediation window to complete. Auditor fieldwork would then commence in early August 2026, with the final Type 1 report likely available by end September 2026 — within the contractual six-month window.	[23](#_toc84)

\11. Conclusion and Next Steps	[24](#_toc85)

MeridianHealth Analytics Pty Ltd is well-positioned to achieve SOC 2 Type 1 audit readiness within the 90-day window required by its US healthcare customer commitments. The existing ISO 27001:2022 ISMS provides 82% direct control reuse, and the 22 findings raised through this assessment are all addressable within the proposed sprint cadence.	[25](#_toc86)

Successful execution of the recommended remediation roadmap, combined with timely auditor selection and adequate evidence retention, supports a Type 1 “as-of” date of 31 July 2026 and final report delivery by end September 2026.	[26](#_toc87)

11.1 Immediate Next Steps	[26](#_toc88)

11.2 Acknowledgements	[26](#_toc89)

The practitioner thanks the CISO, CTO, and the broader MeridianHealth Engineering, Platform, Security, People & Culture, and General Counsel teams for their open and cooperative engagement throughout the assessment.	[26](#_toc90)

\12. Appendices	[27](#_toc91)

Appendix A — Companion Artefacts	[27](#_toc92)

This Report is accompanied by the following separately delivered artefacts:	[27](#_toc93)

Appendix B — Glossary	[27](#_toc94)

Appendix C — Frameworks Referenced	[27](#_toc95)



<a name="_toc"></a>**1. Executive Summary\
\
\
MeridianHealth Analytics Pty Ltd (“MeridianHealth”) engaged the practitioner to perform a SOC 2 Type 1 Readiness Assessment against the AICPA Trust Services Criteria — Security (Common Criteria CC1 through CC9). The engagement objective was to assess the design of MeridianHealth's controls, identify gaps requiring remediation, and produce a roadmap to position MeridianHealth for a successful Type 1 examination by an independent CPA firm.\
\
\
MeridianHealth holds an active ISO/IEC 27001:2022 certification and operates a mature Information Security Management System (ISMS). The engagement made extensive use of existing ISMS artefacts to minimise duplication of effort. The assessment evaluated 65 controls across the nine Common Criteria categories and mapped 93 ISO 27001:2022 Annex A controls to SOC 2 Security TSC criteria.**
## <a name="_toc1"></a>**1.1 Headline Findings**

|**Total controls assessed**|**65**|
| :- | :- |
|**Implemented**|38 (59%)|
|**Partially Implemented**|25 (38%)|
|**Not Implemented**|1 (2%)|
|**Not Applicable**|1 (2%)|
|**ISO 27001:2022 control reuse for SOC 2**|**82.4% Full reuse, 17.6% Partial reuse**|
|**Findings raised**|**22 (4 High, 17 Medium, 1 Low)**|
|**Estimated remediation effort**|155 person-days across 90 days / 6 sprints|
##
## <a name="_toc2"></a>**1.2 Overall Readiness Position**
## <a name="_toc3"></a>**MeridianHealth's existing ISMS provides a strong foundation for SOC 2 Type 1. The maturity of the ISO 27001 ISMS, combined with modern cloud-native infrastructure and a security-conscious engineering culture, means the gap to SOC 2 Type 1 audit readiness is manageable.**
## <a name="_toc4"></a>**All four High-severity findings can be closed within the first two-week sprint. With successful execution of the recommended 90-day remediation roadmap, MeridianHealth is on track to achieve Type 1 audit readiness by 28 July 2026, in line with the contractual commitment to BlueRidge Health Plan and Cascadia Health.**
## <a name="_toc5"></a>**1.3 Key Strengths**
- Existing ISO 27001:2022 certification provides 82% direct control reuse, minimising net-new build.
- Strong technical control posture across logical access (CC6) and system operations (CC7) underpinned by AWS-native tooling and continuous monitoring.
- Mature change management process with 100% infrastructure-as-code coverage and mandatory peer review.
- Engaged executive sponsorship with quarterly Board-level security reporting.
## <a name="_toc6"></a>**1.4 Key Areas for Action**
- Move user access reviews from annual to quarterly cadence (CC6.2).
- Drive security awareness training to 100% completion and enable phishing simulation (CC1.4).
- Define and contractually commit to a 72-hour incident notification SLA (CC2.3).
- Build a Complementary User Entity Control (CUEC) tracker for sub-service organisations (CC9.2).
- Refresh four stale policies and adopt a documented annual review cadence (CC5.3).

<a name="_toc7"></a>**2. Engagement Scope and Approach**
## <a name="_toc8"></a>**2.1 Objectives**
## <a name="_toc9"></a>**The engagement was conducted to:**
- Assess the design of MeridianHealth's controls against the AICPA Trust Services Criteria — Security.
- Identify gaps requiring remediation prior to Type 1 audit fieldwork.
- Maximise reuse of existing ISO 27001:2022 ISMS controls.
- Produce a prioritised remediation roadmap with owners, target dates, and effort estimates.
- Deliver Board-ready Executive Summary and Risk Scorecard.
## <a name="_toc10"></a>**2.2 In Scope**
- Trust Services Criterion: Security (Common Criteria CC1 through CC9).
- System: MeridianHealth Analytics Platform (production) hosted on AWS ap-southeast-2 and us-east-1.
- Supporting infrastructure: Okta, AWS IAM Identity Center, GitHub Enterprise, Jira, Confluence, ServiceNow, BambooHR, Datadog, AWS GuardDuty, AWS Security Hub, CrowdStrike Falcon, Jamf, Microsoft Intune.
- Personnel: All 87 employees and contractors with logical or physical access to the production environment.
- Locations: Sydney (head office) and Melbourne (engineering office).
## <a name="_toc11"></a>**2.3 Out of Scope**
- Trust Services Criteria for Availability, Processing Integrity, and Privacy (deferred to a future Type 2 engagement).
- Confidentiality criterion (assessed at high level only).
- Operating effectiveness testing (a Type 2 activity).
- Penetration testing or vulnerability scanning execution.
- Sub-service organisations (AWS, Okta, Datadog) carved out of the system boundary.
## <a name="_toc12"></a>**2.4 Assessment Approach**
## <a name="_toc13"></a>**The engagement followed a five-phase approach over an eight-week period:**

|**Phase**|**Weeks**|**Activities**|
| :- | :- | :- |
|**Mobilisation**|W1|Kick-off, stakeholder identification, document request list, system description drafting.|
|**Assessment**|W2–W5|Control walkthroughs, evidence inspection, ISO 27001 crosswalk, control rating, gap identification.|
|**Findings**|W6–W7|Findings validation, remediation planning, policy gap drafting, management response collection.|
|**Reporting**|W8|Final report, Executive Summary, Risk Scorecard, walkthrough with leadership and Audit Committee.|
##
<a name="_toc14"></a>**3. System Description**
## <a name="_toc15"></a>**3.1 Entity Overview**
## <a name="_toc16"></a>**MeridianHealth Analytics Pty Ltd is a Sydney-based SaaS provider of healthcare analytics dashboards for private health insurers. Founded in 2019, the company operates with 87 personnel across Sydney (62), Melbourne (18), and remote locations across Australia (7).**
## <a name="_toc17"></a>**The MeridianHealth Analytics Platform ingests claims data from health insurer customers and produces analytics covering fraud detection, utilisation analytics, and member risk scoring. As of April 2026, MeridianHealth serves six Australian private health insurer customers and two newly contracted US health insurance customers (BlueRidge Health Plan and Cascadia Health).**
## <a name="_toc18"></a>**3.2 Services in Scope**
## <a name="_toc19"></a>**The MeridianHealth Analytics Platform comprises:**
- A multi-tenant data ingestion service that accepts claims and member data from customer insurance core systems.
- An analytics engine producing fraud detection, utilisation, and risk-scoring outputs.
- A customer-facing web dashboard for analytics consumption.
- A read-only API used by customers to embed analytics into their own systems.
## <a name="_toc20"></a>**3.3 Infrastructure**
## <a name="_toc21"></a>**MeridianHealth operates a fully cloud-native architecture on Amazon Web Services. Production workloads run in ap-southeast-2 (Sydney) for Australian customers and us-east-1 (N. Virginia) for US customers, with logical separation of customer data by region of residence.**

|**Layer**|**Components**|
| :- | :- |
|**Compute**|Amazon EKS (Kubernetes), AWS Lambda, AWS Fargate.|
|**Data**|Amazon RDS PostgreSQL (multi-AZ), Amazon S3 (encrypted, versioned), Amazon Redshift (analytics).|
|**Network**|AWS VPC with private subnets, AWS WAF, Cloudflare DDoS, default-deny security groups, AWS PrivateLink for cross-account access.|
|**Identity**|Okta (SSO + MFA), AWS IAM Identity Center, GitHub Enterprise, BambooHR (HRIS source of truth).|
|**Security & Monitoring**|AWS GuardDuty, AWS Security Hub, AWS Config, Datadog SIEM, CrowdStrike Falcon EDR, Qualys VMDR.|
|**Endpoint**|Jamf (macOS), Microsoft Intune (Windows), CrowdStrike Falcon agent on all endpoints.|
|**DevOps**|GitHub Enterprise, GitHub Actions, Terraform Cloud, Snyk (SCA + SAST), AWS Systems Manager.|
##
## <a name="_toc22"></a>**3.4 Sub-Service Organisations (Carved Out)**
## <a name="_toc23"></a>**The following sub-service organisations are carved out of the system boundary. Reliance is placed on their published independent assurance reports:**
- Amazon Web Services (AWS) — SOC 2 Type 2 report obtained and reviewed.
- Okta — SOC 2 Type 2 report obtained and reviewed.
- Datadog — SOC 2 Type 2 report obtained and reviewed.

Complementary User Entity Controls (CUECs) defined by these organisations are tracked separately (refer to Finding F-004).
## <a name="_toc24"></a>**3.5 Personnel**
## <a name="_toc25"></a>**MeridianHealth's 87 personnel are organised into Engineering (38), Customer Operations (21), Commercial (14), People & Culture (5), Finance (5), and Executive (4). All personnel undergo background checks at hire (per Checkr integration) and annual security awareness training (per KnowBe4).**
<a name="_toc26"></a>**4. Methodology**
## <a name="_toc27"></a>**4.1 Frameworks Applied**
- AICPA Trust Services Criteria 2017, with revised 2022 points of focus.
- AICPA SOC 2 Description Criteria 2018.
- ISO/IEC 27001:2022 (for crosswalk to existing ISMS controls).
- NIST Cybersecurity Framework 2.0 (referenced for control language).
## <a name="_toc28"></a>**4.2 Evidence Inspection**
## <a name="_toc29"></a>**For each of the 65 controls assessed, the practitioner performed at least one of: control owner interview, documentation review, screen-share walkthrough of the operating system or tool, sample evidence extraction, or live observation. Evidence was rated for reliability on a three-tier scale:**

|**A — High**|System-generated, tamper-evident, complete population (e.g., automated logs, IdP exports, ticketing system extracts).|
| :- | :- |
|**B — Moderate**|Documented and reviewed but partly manual (e.g., signed-off policies, completed checklists).|
|**C — Low**|Self-attested, verbal, or sample-only evidence requiring strengthening before audit.|
##
## <a name="_toc30"></a>**4.3 Control Status Rating**

|**Implemented**|Control is designed appropriately and operating evidence is available.|
| :- | :- |
|**Partially Implemented**|Control exists but is missing key elements (documentation, evidence, or coverage).|
|**Not Implemented**|Control does not exist or has fundamental design gaps.|
|**Not Applicable**|Control does not apply given the entity's services or scope.|
##
## <a name="_toc31"></a>**4.4 Residual Risk Rating**
## <a name="_toc32"></a>**Each control with a status of Partial or Not Implemented was assigned a residual risk rating reflecting the likelihood of an audit exception and the magnitude of remediation required. Ratings: High, Medium, Low, None.**
<a name="_toc33"></a>**5. Summary of Findings**
## <a name="_toc34"></a>**5.1 Findings Profile**
## <a name="_toc35"></a>**Twenty-two findings were raised across the engagement, summarised below:**

|**Severity**|**Count**|**Indicative Theme**|
| :- | :- | :- |
|**High**|**4**|Audit-blocking issues to be addressed in Sprint 1.|
|**Medium**|**17**|Material gaps requiring remediation across Sprints 2–5.|
|**Low**|**1**|Informational; addressed during Sprint 5.|
|**Total**|**22**||
##
## <a name="_toc36"></a>**5.2 Findings Heatmap by Common Criteria**
## <a name="_toc37"></a>**The distribution of findings across the nine Common Criteria categories is shown below. CC6 (Logical Access), CC7 (System Operations), and CC9 (Risk Mitigation) account for the majority of findings, consistent with industry patterns for first-time SOC 2 readiness.**

|**CC**|**Category**|**High**|**Medium**|**Total**|
| :- | :- | :- | :- | :- |
|**CC1**|Control Environment|1|1|**2**|
|**CC2**|Communication & Information|1|1|**2**|
|**CC3**|Risk Assessment|0|1|**1**|
|**CC4**|Monitoring Activities|0|1|**1**|
|**CC5**|Control Activities|0|2|**2**|
|**CC6**|Logical & Physical Access|1|2|**3**|
|**CC7**|System Operations|0|4|**4**|
|**CC8**|Change Management|0|1|**1**|
|**CC9**|Risk Mitigation|1|4|**5**|
##
<a name="_toc38"></a>**6. Detailed Findings by Common Criteria\
\
This section presents findings by Common Criteria category. Full finding details (description, recommendation, owner, target date, effort) are provided in the separate Findings Register & Roadmap workbook.**
## <a name="_toc39"></a>**6.1 CC1 — Control Environment**
## <a name="_toc40"></a>**Two findings were raised. The High-severity finding (F-001) relates to security awareness training completion at 78% (target 100%) and the absence of phishing simulation. SOC 2 audit pattern is full population coverage with retained per-user evidence, supplemented by phishing exercise evidence.**
## <a name="_toc41"></a>**F-005 (Medium) reflects the absence of a Board-approved Information Security Charter and Risk Appetite Statement. While the Board receives quarterly security updates, formal documentation of Board-level risk appetite is required by the SOC 2 audit pattern.**
## <a name="_toc42"></a>**6.2 CC2 — Communication and Information**
## <a name="_toc43"></a>**Two findings were raised. F-002 (High) is the absence of a defined customer incident notification SLA. The current MSA references “reasonable timeframes”, which does not satisfy US healthcare client expectations. A 72-hour SLA aligned with HIPAA breach notification practice is recommended.**
## <a name="_toc44"></a>**F-006 (Medium) is the absence of a customer-facing Trust Centre. While not a strict SOC 2 requirement, US enterprise customers increasingly expect a public Trust Centre publishing assurance status, sub-processors, and incident commitments.**
## <a name="_toc45"></a>**6.3 CC3 — Risk Assessment**
## <a name="_toc46"></a>**F-007 (Medium) reflects the absence of a documented fraud risk assessment. SOC 2 (linked to COSO) expects fraud risk to be considered in the broader risk assessment process, even where not material to the entity.**
## <a name="_toc47"></a>**6.4 CC4 — Monitoring Activities**
## <a name="_toc48"></a>**F-008 (Medium) is the absence of an internal audit function independent of management. ISO 27001 surveillance audits provide some independent assurance, but SOC 2 expects a separate internal audit function. Engagement of an external internal-audit provider is recommended.**
## <a name="_toc49"></a>**6.5 CC5 — Control Activities**
## <a name="_toc50"></a>**F-009 (Medium) covers four policies (DLP, Cryptography, Mobile Device, Acceptable Use) over 24 months old without review. F-010 (Medium) is the absence of a documented Segregation of Duties matrix; SoD is observed in practice (mandatory peer review on production changes) but not formally documented or reviewed.**
## <a name="_toc51"></a>**6.6 CC6 — Logical and Physical Access Controls**
## <a name="_toc52"></a>**Three findings were raised in the most-tested SOC 2 area. F-003 (High) is the most material: user access reviews are performed annually rather than the SOC 2 audit pattern of quarterly reviews with retained manager sign-off.**
## <a name="_toc53"></a>**F-011 (Medium) is the absence of a Privileged Access Management (PAM) tool for OS-level administrative access. AWS console access is mediated via IAM Identity Center with break-glass; OS-level admin on EC2 instances lacks session recording. F-012 (Medium) is the absence of a service account inventory.**
## <a name="_toc54"></a>**6.7 CC7 — System Operations**
## <a name="_toc55"></a>**Four Medium-severity findings were raised. F-013 covers a backlog of 12 High-severity vulnerabilities open beyond their 30-day SLA. F-014 covers an overdue incident response tabletop exercise (last conducted September 2024). F-015 covers the absence of a documented Communications Playbook for incident response. F-016 covers the absence of a recent (within 12 months) full backup recovery test.**
## <a name="_toc56"></a>**6.8 CC8 — Change Management**
## <a name="_toc57"></a>**F-017 (Medium) is the only finding in this category: change evidence (GitHub PRs, Jira tickets) is retained for 6 months by default, while SOC 2 fieldwork typically requires 12+ months of change evidence available for sample testing.**
## <a name="_toc58"></a>**6.9 CC9 — Risk Mitigation**
## <a name="_toc59"></a>**Five findings were raised. F-004 (High) is the absence of a Complementary User Entity Control (CUEC) tracker for AWS, Okta, and Datadog. SOC 2 fieldwork involves auditor verification that CUECs are mapped and addressed.**
## <a name="_toc60"></a>**F-018 (Medium) is the absence of a recent BCP test. F-019 (Medium) is an untested cross-region DR failover. F-020 (Medium) covers the absence of continuous vendor monitoring. F-021 (Medium) covers incomplete automation of data retention and deletion.**
<a name="_toc61"></a>**7. Control Coverage Analysis**
## <a name="_toc62"></a>**7.1 Coverage by Common Criteria Category**
## <a name="_toc63"></a>**Control coverage was strongest in CC1 (Control Environment, 71% Implemented) and CC6 (Logical Access, 67% Implemented — weighted down by partial PAM and access review findings). Coverage was weakest in CC4 (Monitoring Activities), CC5 (Control Activities), and CC9 (Risk Mitigation), each at 50% Implemented.**

|**CC**|**Category**|**Total**|**Impl.**|**Partial**|**N/A**|**% Impl.**|
| :- | :- | :- | :- | :- | :- | :- |
|**CC1**|Control Environment|7|5|2|0|**71%**|
|**CC2**|Communication & Information|5|3|2|0|**60%**|
|**CC3**|Risk Assessment|5|3|1|0|**60%**|
|**CC4**|Monitoring Activities|4|2|2|0|**50%**|
|**CC5**|Control Activities|4|2|2|0|**50%**|
|**CC6**|Logical & Physical Access|13|8|4|1|**67%**|
|**CC7**|System Operations|10|6|4|0|**60%**|
|**CC8**|Change Management|5|3|2|0|**60%**|
|**CC9**|Risk Mitigation|12|6|6|0|**50%**|
|**Total**||**65**|**38**|**25**|**1**|**59%**|
##
## <a name="_toc64"></a>**7.2 Evidence Reliability Distribution**
## <a name="_toc65"></a>**Of the 64 in-scope controls assessed, 26 are supported by A-rated (High reliability) evidence, 27 by B-rated (Moderate) evidence, and 11 by C-rated (Low) evidence. Strengthening C-rated evidence to at least B-rating is a key remediation theme captured in the findings register.**
<a name="_toc66"></a>**8. ISO 27001:2022 Reuse Analysis**

<a name="_toc67"></a>**MeridianHealth's existing ISO 27001:2022 ISMS provides a substantial foundation for SOC 2 Type 1. The detailed crosswalk (refer to ISO 27001 ↔ SOC 2 Crosswalk workbook) maps 93 ISO 27001:2022 Annex A controls against the SOC 2 Security TSC points of focus.**
## <a name="_toc68"></a>**8.1 Reuse Summary**

|**Total ISO 27001:2022 Annex A controls**|**93**|
| :- | :- |
|**Full reuse**|75 controls (82.4% excl. N/A)|
|**Partial reuse**|16 controls (17.6% excl. N/A)|
|**Net-new SOC 2 controls required**|12|
|**Not Applicable**|2 (cloud-only environment exceptions)|
##
## <a name="_toc69"></a>**8.2 Net-New Controls Required**
## <a name="_toc70"></a>**Twelve SOC 2 Security TSC criteria require net-new controls beyond the existing ISMS. These centre on:**
- Board-level governance artefacts (Security Charter, Risk Appetite Statement).
- Customer-facing assurance commitments (Trust Centre, incident SLA).
- Audit-pattern formalisations (quarterly access reviews, fraud risk assessment, independent internal audit).
- Sub-service organisation tracking (CUEC tracker).
- Operational evidence retention (12+ month change evidence).
## <a name="_toc71"></a>**8.3 Strategic Implication**
## <a name="_toc72"></a>**The 82.4% direct reuse rate means MeridianHealth can pursue Type 1 readiness primarily through evidence strengthening and process formalisation rather than building new controls. This significantly reduces the net cost and timeline of SOC 2 readiness compared to an entity without an existing ISMS.**
<a name="_toc73"></a>**9. Remediation Roadmap Summary**

<a name="_toc74"></a>**A 90-day remediation roadmap, structured into six two-week sprints, has been developed to address all 22 findings. Detailed sprint-by-sprint planning is in the Findings Register & Roadmap workbook.**
## <a name="_toc75"></a>**9.1 Sprint Overview**

|**Sprint**|**Theme**|**Findings**|**Effort (days)**|
| :- | :- | :- | :- |
|**Sprint 1**|Quick wins & High-severity remediation|6|41|
|**Sprint 2**|Governance & policies|4|26|
|**Sprint 3**|Process formalisation|5|34|
|**Sprint 4**|Resilience & PAM|3|33|
|**Sprint 5**|Data lifecycle & automation|2|11|
|**Sprint 6**|Buffer & audit prep|0|10|
|**Total**||**22**|**155**|
##
## <a name="_toc76"></a>**9.2 Resource Requirements**
## <a name="_toc77"></a>**Total remediation effort is estimated at 155 person-days across 90 days. Effort concentrates in Security Engineering (35 days), CISO office (28 days), and Platform Engineering (16 days). Most findings can be addressed by existing teams without external resourcing; the recommended PAM rollout (F-011) and external internal-audit engagement (F-008) are the two activities with potential procurement implications.**
<a name="_toc78"></a>**10. Recommendations to Management**
## <a name="_toc79"></a>**10.1 Strategic Recommendations**
## <a name="_toc80"></a>**Beyond the specific findings, three strategic recommendations support sustainable SOC 2 maturity:**
- Adopt a compliance automation platform (Vanta, Drata, or Secureframe) to reduce ongoing evidence collection burden, automate access reviews, and prepare for Type 2.
- Plan now for SOC 2 Type 2 in 2027, with Confidentiality and Availability criteria added to scope. Begin operating the Type 1 controls consistently to build the evidence population required.
- Designate a SOC 2 Programme Lead (separate from the CISO) to coordinate ongoing audit readiness and serve as the primary liaison with auditors.
## <a name="_toc81"></a>**10.2 Auditor Selection**
## <a name="_toc82"></a>**The practitioner is independent of the Type 1 audit firm and does not recommend a specific auditor. Selection criteria to consider include: SaaS sector experience, Australian-US dual capability (some auditors specialise in either jurisdiction), pricing model (fixed-fee versus time-and-materials), and ability to co-ordinate with the existing ISO 27001 certification body to minimise duplicative evidence requests.**
## <a name="_toc83"></a>**10.3 Audit Period Planning**
## <a name="_toc84"></a>**MeridianHealth should aim for a Type 1 “as-of” date of 31 July 2026, allowing the full 90-day remediation window to complete. Auditor fieldwork would then commence in early August 2026, with the final Type 1 report likely available by end September 2026 — within the contractual six-month window.**
<a name="_toc85"></a>**11. Conclusion and Next Steps**

<a name="_toc86"></a>**MeridianHealth Analytics Pty Ltd is well-positioned to achieve SOC 2 Type 1 audit readiness within the 90-day window required by its US healthcare customer commitments. The existing ISO 27001:2022 ISMS provides 82% direct control reuse, and the 22 findings raised through this assessment are all addressable within the proposed sprint cadence.**

<a name="_toc87"></a>**Successful execution of the recommended remediation roadmap, combined with timely auditor selection and adequate evidence retention, supports a Type 1 “as-of” date of 31 July 2026 and final report delivery by end September 2026.**
## <a name="_toc88"></a>**11.1 Immediate Next Steps**
- Endorsement of this Report and the Remediation Roadmap by the CISO and Audit & Risk Committee.
- Sprint 1 kick-off (29 April 2026), prioritising the four High-severity findings.
- Engagement of the Type 1 audit firm by mid-May 2026.
- Adoption of compliance automation platform to support ongoing evidence collection.
- Establishment of weekly progress check-ins between practitioner and CISO during the remediation window.
## <a name="_toc89"></a>**11.2 Acknowledgements**
## <a name="_toc90"></a>**The practitioner thanks the CISO, CTO, and the broader MeridianHealth Engineering, Platform, Security, People & Culture, and General Counsel teams for their open and cooperative engagement throughout the assessment.**
<a name="_toc91"></a>**12. Appendices**
## <a name="_toc92"></a>**Appendix A — Companion Artefacts**
## <a name="_toc93"></a>**This Report is accompanied by the following separately delivered artefacts:**
- Engagement Charter (D1) — Signed.
- Control Matrix Workbook (D2) — 65 controls assessed against TSC Security.
- ISO 27001:2022 ↔ SOC 2 Crosswalk (D3).
- Findings Register & 90-Day Roadmap (D4).
- Policy Pack (D5).
- Executive Summary (D7) — 2-page Board-ready summary.
- Risk Scorecard (D8) — 1-page risk dashboard.
## <a name="_toc94"></a>**Appendix B — Glossary**

|**Term**|**Definition**|
| :- | :- |
|**AICPA**|American Institute of Certified Public Accountants — issuer of the Trust Services Criteria.|
|**CC**|Common Criteria — the nine baseline criteria of the Security TSC (CC1–CC9).|
|**CUEC**|Complementary User Entity Control — control the user entity must implement to complement a sub-service organisation's controls.|
|**DR**|Disaster Recovery.|
|**IdP**|Identity Provider — e.g., Okta, Azure AD.|
|**IR**|Incident Response.|
|**ISMS**|Information Security Management System (ISO 27001 term).|
|**MFA**|Multi-Factor Authentication.|
|**MSA**|Master Services Agreement.|
|**PAM**|Privileged Access Management.|
|**RPO**|Recovery Point Objective.|
|**RTO**|Recovery Time Objective.|
|**SoD**|Segregation of Duties.|
|**SoA**|Statement of Applicability (ISO 27001 term).|
|**TSC**|Trust Services Criteria.|
|**TPRM**|Third-Party Risk Management.|
##
## <a name="_toc95"></a>**Appendix C — Frameworks Referenced**
- AICPA Trust Services Criteria 2017 (revised 2022 points of focus).
- AICPA SOC 2 Description Criteria 2018.
- ISO/IEC 27001:2022 Information security management systems — Requirements.
- ISO/IEC 27002:2022 Information security controls.
- ISO 31000:2018 Risk management.
- NIST Cybersecurity Framework 2.0.



**END OF REPORT**



*PORTFOLIO ARTEFACT — Simulated engagement. MeridianHealth Analytics Pty Ltd is fictional. All findings and persons are illustrative.*
Confidential — Client | Page  of 
