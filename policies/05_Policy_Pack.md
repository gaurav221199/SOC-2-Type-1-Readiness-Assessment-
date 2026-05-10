*Policy Pack — SOC 2 Type 1 Readiness | MeridianHealth Analytics*

**POLICY PACK**

SOC 2 Type 1 Readiness

*MeridianHealth Analytics Pty Ltd*

Engagement: MHA-SOC2-2026-001

|**Document Title**|Policy Pack — SOC 2 Type 1 Readiness|
| :- | :- |
|**Version**|1\.0 — Final|
|**Date Issued**|28 April 2026|
|**Prepared By**|Gaurav Govind, GRC Analyst|
|**Classification**|Confidential — Client|

*PORTFOLIO ARTEFACT — Policies are illustrative work product produced for a simulated engagement. MeridianHealth Analytics Pty Ltd is fictional.*



**Pack Contents**

This Policy Pack contains five core policies required to evidence SOC 2 Type 1 readiness. Each policy includes document control, purpose, scope, statements, roles, and explicit mapping to the AICPA Trust Services Criteria — Security.



|**#**|**Policy**|**Owner**|**Maps to TSC**|
| :- | :- | :- | :- |
|**1**|**Information Security Policy**|Chief Information Security Officer|CC1, CC2, CC5|
|**2**|**Access Control Policy**|Identity & Access Management Lead|CC6|
|**3**|**Incident Response Policy**|Chief Information Security Officer|CC7|
|**4**|**Change Management Policy**|Chief Technology Officer|CC8|
|**5**|**Vendor Management Policy**|Procurement Lead / CISO|CC9|
# **1. Information Security Policy**

|**Policy Owner**|Chief Information Security Officer|**Approver**|Chief Executive Officer|
| :- | :- | :- | :- |
|**Version**|3\.2|**Effective Date**|1 May 2026|
|**Review Cadence**|Annual|**Next Review**|1 May 2027|
|**Classification**|Internal|**Maps to TSC**|CC1, CC2, CC5|


## **1.1 Purpose**
This Policy establishes MeridianHealth Analytics Pty Ltd's commitment to the protection of information assets entrusted to it by customers, employees, regulators, and other stakeholders. It defines the principles, responsibilities, and high-level requirements that govern information security across all MeridianHealth operations.
## **1.2 Scope**
This Policy applies to all employees, contractors, consultants, temporary staff, and other workers at MeridianHealth, including all personnel affiliated with third parties who access or process MeridianHealth or customer information. It applies to all information regardless of medium, including electronic, print, voice, and visual.
## **1.3 Policy Statements**
### **1.3.1 Commitment to Confidentiality, Integrity, and Availability**
MeridianHealth shall implement and maintain reasonable and appropriate administrative, technical, and physical safeguards to preserve the confidentiality, integrity, and availability of all information assets, with particular attention to customer data and protected health information.
### **1.3.2 Risk-Based Approach**
Information security controls shall be selected and implemented based on a documented risk assessment process aligned with ISO 31000 principles. Residual risks shall be reviewed at least annually and accepted at an appropriate management level.
### **1.3.3 Compliance with Laws and Contractual Obligations**
MeridianHealth shall comply with all applicable laws, regulations, and contractual obligations relating to information security, including but not limited to the Privacy Act 1988 (Cth), Australian Privacy Principles, APRA CPS 234 (where applicable to insurer customers), and US sector-specific requirements applicable to customer data.
### **1.3.4 Continuous Improvement**
MeridianHealth maintains an Information Security Management System (ISMS) certified to ISO/IEC 27001:2022. The ISMS shall be subject to continuous improvement through internal audits, management reviews, and remediation of identified weaknesses.
### **1.3.5 Acceptable Behaviour**
All personnel are required to act with integrity, follow MeridianHealth's Code of Conduct, complete annual security awareness training, and acknowledge their security responsibilities annually.
## **1.4 Roles and Responsibilities**
- Chief Executive Officer: Ultimate accountability for information security at MeridianHealth.
- Chief Information Security Officer (CISO): Owns this Policy, the broader ISMS, and the security programme. Reports quarterly to the Audit and Risk Committee.
- Board of Directors: Provides oversight of information security through the Audit and Risk Committee.
- All Personnel: Comply with this Policy and supporting procedures. Report security events promptly through defined channels.
## **1.5 Compliance and Enforcement**
Violations of this Policy may result in disciplinary action up to and including termination of employment or contract. Suspected criminal activity will be reported to law enforcement where appropriate.
## **1.6 Exceptions**
Exceptions to this Policy must be documented, risk-assessed, and approved by the CISO. Exceptions are reviewed at least annually and tracked in the Risk Register.
## **1.7 Related Documents**
- Acceptable Use Policy
- Access Control Policy (Section 2)
- Incident Response Policy (Section 3)
- Change Management Policy (Section 4)
- Vendor Management Policy (Section 5)
- Risk Management Standard
- Code of Conduct
# **2. Access Control Policy**

|**Policy Owner**|Identity & Access Management Lead|**Approver**|Chief Information Security Officer|
| :- | :- | :- | :- |
|**Version**|2\.4|**Effective Date**|1 May 2026|
|**Review Cadence**|Annual|**Next Review**|1 May 2027|
|**Classification**|Internal|**Maps to TSC**|CC6|


## **2.1 Purpose**
This Policy defines the principles and requirements for granting, modifying, reviewing, and removing access to MeridianHealth information systems and data. It supports the principle of least privilege and ensures access is commensurate with business need.
## **2.2 Scope**
This Policy applies to logical access to all in-scope systems including AWS production accounts, the MeridianHealth Analytics Platform, GitHub Enterprise, Okta, and supporting SaaS applications. It also covers physical access to MeridianHealth offices.
## **2.3 Policy Statements**
### **2.3.1 Identity Management**
- Each user shall have a unique, individually assigned identity. Shared accounts are prohibited except where technically unavoidable; such accounts must be inventoried, owned, and reviewed quarterly.
- Identities shall be provisioned only following documented authorisation through the People & Culture onboarding workflow or a ServiceNow access request.
- Identities shall be deprovisioned within four (4) business hours of termination of employment or contract.
### **2.3.2 Authentication**
- Multi-factor authentication (MFA) is mandatory for all access to in-scope systems. MFA shall be enforced through Okta (SSO applications) and AWS IAM Identity Center (cloud console access).
- Passwords shall meet a minimum length of fourteen (14) characters with complexity requirements; passwords shall be rotated at least every ninety (90) days for privileged accounts.
- Sessions shall time out after no more than twenty-four (24) hours of inactivity.
### **2.3.3 Authorisation and Least Privilege**
- Access shall be granted based on the principle of least privilege, aligned to documented role definitions.
- Privileged access (administrator, root, database owner) requires additional approval from the CISO or delegate and is reviewed quarterly.
- Standing privileged access shall be minimised in favour of just-in-time elevation through AWS IAM Identity Center or PAM tooling.
### **2.3.4 Access Reviews**
- All user access to in-scope systems shall be reviewed by the relevant manager at least quarterly.
- Privileged access shall be reviewed at least quarterly.
- Service account access shall be reviewed at least quarterly, with confirmation of continued business need by the named owner.
- Evidence of review and sign-off shall be retained for a minimum of two (2) years.
### **2.3.5 Physical Access**
- Physical access to MeridianHealth offices is controlled through Kisi access control. Access cards are issued upon hire and revoked at termination.
- Visitors shall be logged at reception and escorted at all times within secure areas.
- Production data centre access is not applicable; production workloads are hosted at AWS, with reliance placed on AWS's SOC 2 Type 2 report.
## **2.4 Roles and Responsibilities**
- Identity & Access Management Lead: Owns this Policy and the access management process.
- People & Culture: Triggers provisioning and deprovisioning workflows from BambooHR.
- Managers: Authorise role-based access, conduct quarterly access reviews.
- CISO: Approves privileged access; reviews access review evidence; addresses exceptions.
## **2.5 Compliance and Enforcement**
Non-compliance with this Policy may result in disciplinary action and revocation of access. Repeated or material non-compliance is reported to the CISO and Audit and Risk Committee.
## **2.6 Exceptions**
Exceptions must be documented in the Access Exceptions Register, approved by the CISO, time-bounded (maximum twelve months), and reviewed at expiry.
# **3. Incident Response Policy**

|**Policy Owner**|Chief Information Security Officer|**Approver**|Chief Executive Officer|
| :- | :- | :- | :- |
|**Version**|3\.0|**Effective Date**|1 May 2026|
|**Review Cadence**|Annual|**Next Review**|1 May 2027|
|**Classification**|Internal|**Maps to TSC**|CC7|


## **3.1 Purpose**
This Policy defines MeridianHealth's approach to identifying, responding to, recovering from, and learning from information security incidents. It supports timely containment and effective communication with affected parties.
## **3.2 Scope**
This Policy applies to all suspected or confirmed security incidents affecting MeridianHealth systems, data, or operations, including those involving sub-service organisations and vendors.
## **3.3 Policy Statements**
### **3.3.1 Incident Detection and Reporting**
- All personnel are required to report suspected security incidents immediately via the security@meridianhealth.com.au mailbox or the #security-alerts Slack channel.
- Automated detection through Datadog SIEM, AWS GuardDuty, AWS Security Hub, and CrowdStrike Falcon shall escalate alerts to the on-call Security Engineer 24x7.
### **3.3.2 Severity Classification**
Incidents are classified into four severity levels:

- P1 — Critical: Confirmed unauthorised access to production data, customer-impacting outage, or active malware in production. Response within 15 minutes; CEO notified.
- P2 — High: Suspected unauthorised access, significant data exposure, or partial production outage. Response within 1 hour; CISO notified.
- P3 — Medium: Contained security event with no customer or data impact. Response within 4 hours during business hours.
- P4 — Low: Informational events requiring investigation but no immediate action.
### **3.3.3 Response Process**
- The Incident Commander (typically the CISO or delegate) leads incident response.
- Response follows the documented Incident Response Plan, which includes containment, eradication, recovery, and post-incident review phases.
- All response activities, decisions, and communications shall be logged in real time in the incident channel and consolidated into a post-incident report.
### **3.3.4 Customer and Regulatory Notification**
- MeridianHealth shall notify affected customers of any incident materially affecting the confidentiality, integrity, or availability of their data within seventy-two (72) hours of confirmation.
- Regulatory notifications shall be made in line with applicable obligations including the Notifiable Data Breaches scheme under the Privacy Act 1988 and US state breach notification laws as applicable to customer data.
- All external communications must be approved by the General Counsel and CISO prior to release.
### **3.3.5 Testing and Continuous Improvement**
- Tabletop exercises shall be conducted at least every six (6) months.
- Post-incident reviews (blameless post-mortems) shall be conducted for all P1 and P2 incidents and recorded in Confluence.
- Lessons learned shall be tracked to closure with assigned owners and target dates.
## **3.4 Roles and Responsibilities**
- CISO: Owns this Policy and incident response programme; serves as Incident Commander or delegates the role.
- Security Operations on-call: First responder for automated alerts; performs initial triage and severity classification.
- Engineering and Platform teams: Provide technical response and remediation.
- General Counsel and CEO: Approve external communications for P1 and P2 incidents.
- People & Culture: Supports HR-related incidents.
## **3.5 Compliance and Enforcement**
Failure to report a security incident is a serious violation of this Policy and may result in disciplinary action.
## **3.6 Exceptions**
No exceptions to incident reporting requirements. Exceptions to specific response timelines may be granted by the CISO during active incidents based on operational reality.
# **4. Change Management Policy**

|**Policy Owner**|Chief Technology Officer|**Approver**|Chief Information Security Officer|
| :- | :- | :- | :- |
|**Version**|2\.7|**Effective Date**|1 May 2026|
|**Review Cadence**|Annual|**Next Review**|1 May 2027|
|**Classification**|Internal|**Maps to TSC**|CC8|


## **4.1 Purpose**
This Policy defines the requirements for authorising, testing, deploying, and recording changes to MeridianHealth production systems and applications, with the objective of preventing unauthorised changes and minimising the risk of service disruption.
## **4.2 Scope**
This Policy applies to all changes to in-scope production systems, including the MeridianHealth Analytics Platform application code, infrastructure-as-code definitions, configuration changes, and database schema changes.
## **4.3 Policy Statements**
### **4.3.1 Change Authorisation**
- All production changes shall be tracked in Jira with a unique change ticket.
- All code changes shall be submitted as a GitHub Pull Request and require at least one independent peer review prior to merge.
- Infrastructure changes (Terraform) shall require a successful plan review and approval from a Platform Engineering reviewer prior to apply.
- Production database schema changes require additional review from a Senior Engineer or DBA.
### **4.3.2 Change Testing**
- All changes shall pass automated unit tests, integration tests, and security tests (SAST, dependency scan) in the CI/CD pipeline.
- Material changes shall be deployed to and validated in the staging environment prior to production deployment.
- Test evidence shall be retained for a minimum of twenty-four (24) months.
### **4.3.3 Emergency Changes**
- Emergency changes (those required to remediate a P1 incident or production outage) may be deployed without prior peer review.
- Emergency changes shall be retrospectively reviewed and ticketed within twenty-four (24) hours of deployment.
- Emergency changes shall be reported to the CTO and CISO weekly and reviewed quarterly to identify systemic issues.
### **4.3.4 Configuration Management**
- All infrastructure shall be defined as code (Terraform). Manual changes to production are prohibited except for emergency response.
- Drift between code and deployed state shall be detected and reconciled within five (5) business days.
- All production configuration shall be subject to version control in GitHub Enterprise.
### **4.3.5 Segregation of Duties**
- Personnel who author a change cannot also be the sole approver of that change.
- Personnel who deploy production changes shall be distinct from those who authorise the underlying business request, where practicable.
## **4.4 Roles and Responsibilities**
- Chief Technology Officer: Owns this Policy.
- Engineering Managers: Ensure compliance with the Pull Request review process within their teams.
- Platform Engineering: Maintains the CI/CD pipeline, drift detection, and infrastructure-as-code standards.
- CISO: Reviews emergency change reports and segregation of duties exceptions.
## **4.5 Compliance and Enforcement**
Non-compliance with this Policy is reported through the Engineering chain of command and to the CISO. Persistent or material non-compliance is escalated to the CTO.
## **4.6 Exceptions**
Exceptions are documented in the Change Exceptions Register, approved by the CTO, and reviewed quarterly by the CISO.
# **5. Vendor Management Policy**

|**Policy Owner**|Procurement Lead / CISO|**Approver**|Chief Operating Officer|
| :- | :- | :- | :- |
|**Version**|2\.1|**Effective Date**|1 May 2026|
|**Review Cadence**|Annual|**Next Review**|1 May 2027|
|**Classification**|Internal|**Maps to TSC**|CC9|


## **5.1 Purpose**
This Policy defines the requirements for assessing, contracting, monitoring, and offboarding vendors and third parties that process MeridianHealth or customer data, or that provide services material to MeridianHealth's operations.
## **5.2 Scope**
This Policy applies to all third parties engaged by MeridianHealth, including SaaS providers, cloud sub-service organisations, contractors with system access, and material business service providers.
## **5.3 Policy Statements**
### **5.3.1 Vendor Tiering**
- Tier 1: Vendors processing customer data or providing services critical to production operations (e.g., AWS, Okta, Datadog). Highest level of due diligence and ongoing monitoring.
- Tier 2: Vendors with access to internal MeridianHealth data or systems (e.g., BambooHR, GitHub Enterprise). Standard due diligence.
- Tier 3: Vendors providing peripheral services with limited data access (e.g., office supplies). Lightweight due diligence.
### **5.3.2 Pre-Engagement Due Diligence**
- Tier 1 and Tier 2 vendors shall complete a Consensus Assessments Initiative Questionnaire (CAIQ) or equivalent prior to contracting.
- Tier 1 vendors shall provide a current SOC 2 Type 2 report or equivalent independent assurance.
- Findings from due diligence shall be reviewed by the CISO and documented in the Vendor Risk Register.
### **5.3.3 Contractual Requirements**
- Tier 1 and Tier 2 contracts shall include a Data Processing Agreement and Security Addendum covering: data handling, breach notification, audit rights, sub-processor approval, and termination assistance.
- Tier 1 vendors processing customer data shall be disclosed in the customer Master Services Agreement as sub-processors.
### **5.3.4 Ongoing Monitoring**
- Tier 1 vendors shall be subject to continuous monitoring through a security ratings service (e.g., SecurityScorecard, BitSight).
- Tier 1 vendor SOC reports shall be reviewed annually; Complementary User Entity Controls shall be tracked and mapped to MeridianHealth controls.
- Tier 2 vendors shall be reassessed annually.
### **5.3.5 Offboarding**
- Vendor offboarding shall include: revocation of access, certified destruction or return of data, confirmation in writing, and update to the Vendor Register.
## **5.4 Roles and Responsibilities**
- Procurement Lead: Owns the vendor lifecycle process; coordinates due diligence and contract execution.
- CISO: Reviews and approves Tier 1 vendor security posture; approves SOC report findings.
- General Counsel: Reviews and approves contractual terms.
- Business Owners: Identify continued business need for vendor at annual review.
## **5.5 Compliance and Enforcement**
Engagement of vendors outside this Policy (“shadow IT”) is prohibited. Discovered cases shall be brought into compliance or terminated.
## **5.6 Exceptions**
Exceptions must be documented, risk-assessed, approved by the CISO, and reviewed at least annually.



*PORTFOLIO ARTEFACT — Policies are illustrative work product produced for a simulated engagement. MeridianHealth Analytics Pty Ltd is fictional. Specific tools, vendors, and parameters referenced are representative of typical SaaS environments.*
Confidential — Client | Page  of 
