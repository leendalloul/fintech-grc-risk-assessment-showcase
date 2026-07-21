# Complete Risk and Compliance Assessment

## Scenario

NoorPay is a fictional Saudi fintech company providing digital-payment and e-wallet services. The academic scenario assumes sensitive financial data, cloud-security weaknesses, informal governance, an undocumented previous breach, and preparation for a regulatory audit.

## 1. Risk Assessment

The assessment follows NIST SP 800-30 concepts and uses a qualitative 5×5 likelihood-and-impact matrix. Eight technology, people, process, governance, and compliance risks were identified.

### Complete Risk Register

| ID | Risk description | Affected asset | Threat source | Likelihood | Impact | Risk rating | Risk level |
| --- | --- | --- | --- | --- | --- | --- | --- |
| R.01 | Unauthorized access to customer financial data due to weak cloud-security controls | Customer data and cloud infrastructure | External attackers | High | Very High | Very High | Very High |
| R.02 | Lack of a formal risk-management process | Organizational risk-management process | Internal mismanagement | High | High | High | High |
| R.03 | Non-compliance with GDPR and Saudi PDPL requirements | Customer data | Regulatory authorities | High | Very High | Very High | Very High |
| R.04 | Undocumented previous data breach leading to repeated vulnerabilities | Incident response and customer data | External attackers | High | Very High | Very High | Very High |
| R.05 | Weak access control caused by the absence of security leadership | Access-control systems | External attackers or insider threats | High | High | High | High |
| R.06 | Cloud misconfiguration leading to data exposure | Cloud infrastructure | External attackers | High | Very High | Very High | Very High |
| R.07 | Human error caused by insufficient security awareness | Employee accounts | Phishing or social engineering | High | High | High | High |
| R.08 | Absence of a formal cloud-security policy | Cloud infrastructure | External attackers | High | High | High | High |

### Risk Prioritization

The three most urgent scenario risks are:

1. **Unauthorized access to customer financial data:** potential financial loss, regulatory penalties, and reputational damage.
2. **GDPR and Saudi PDPL non-compliance:** potential audit failure, penalties, and loss of customer trust.
3. **Undocumented previous breach:** unresolved root causes may allow the same weaknesses to be exploited again.

### Risk Heat Map

All eight scenario risks were assessed as having High likelihood. Their impact distribution is shown below.

| Likelihood \ Impact | Very Low | Low | Medium | High | Very High |
| --- | ---: | ---: | ---: | ---: | ---: |
| Very High | — | — | — | — | — |
| High | — | — | — | R.02, R.05, R.07, R.08 | R.01, R.03, R.04, R.06 |
| Medium | — | — | — | — | — |
| Low | — | — | — | — | — |
| Very Low | — | — | — | — | — |

## 2. Compliance Gap Analysis

### GDPR Requirements Mapping

| Requirement | Why it applies | Status | Scenario justification |
| --- | --- | --- | --- |
| Data Protection by Design — Article 25 | Financial data is processed in cloud systems | Non-compliant | No formal cloud-security policy is described |
| Security of Processing — Article 32 | Requires measures such as encryption and access control | Non-compliant | Weak cloud controls and misconfiguration risk |
| Breach Notification — Article 33 | Requires a defined notification process | Non-compliant | Previous breach was not documented |
| Accountability — Article 5(2) | Organization must demonstrate compliance | Non-compliant | No formal risk register or governance evidence |
| Access Control and Authentication | Protects customer and employee accounts | Partially compliant | Some access control exists, but governance is weak |
| Data Minimization — Article 5(1) | Limits unnecessary collection and retention | Partially compliant | No clear evidence of enforcement |

### Saudi PDPL Requirements Mapping

| Requirement | Why it applies | Status | Scenario justification |
| --- | --- | --- | --- |
| Personal-data protection controls | Core requirement for financial services | Non-compliant | Weak security and cloud controls |
| Breach-notification governance | Requires structured incident reporting | Non-compliant | Previous breach was undocumented |
| Data-processing governance | Requires policies, ownership, and accountability | Non-compliant | No CISO or formal governance structure |
| Consent and data handling | Requires controlled personal-data processing | Partially compliant | No clear policy is described |
| Data-retention policy | Requires controlled retention practices | Partially compliant | Retention is not addressed by the scenario |
| Third-party data protection | Cloud providers introduce shared responsibility | Non-compliant | No cloud-security or vendor-control policy |

Regulatory requirements may change. This academic mapping is not legal advice and should not be used as a substitute for current guidance from regulators or qualified counsel.

### Complete Gap Analysis

| Regulation | Requirement | Current status | Evidence from scenario | Gap |
| --- | --- | --- | --- | --- |
| GDPR | Security of Processing | Non-compliant | Cloud-misconfiguration risk | Missing technical controls such as encryption and mature IAM |
| GDPR | Breach Notification | Non-compliant | Breach was not documented | No formal incident-reporting process |
| GDPR | Accountability | Non-compliant | No formal risk register | Missing governance documentation and evidence |
| Saudi PDPL | Data-protection controls | Non-compliant | Weak cloud security | Insufficient protection mechanisms |
| Saudi PDPL | Governance structure | Non-compliant | No CISO | No defined security leadership |
| Saudi PDPL | Third-party protection | Non-compliant | Cloud provider is unmanaged | No vendor-security controls |

### Most Critical Gaps

#### Gap 1 — No breach-notification process

- **Consequence:** regulatory exposure and possible audit failure
- **Business impact:** loss of trust and delayed incident decisions

#### Gap 2 — Weak cloud-security controls

- **Consequence:** greater likelihood of data exposure
- **Business impact:** high financial, legal, and operational risk

#### Gap 3 — Missing governance and security leadership

- **Consequence:** unclear accountability and inconsistent decisions
- **Business impact:** every other risk becomes more difficult to manage

## 3. Remediation Roadmap

### Immediate — 0 to 1 month

**Implement an incident-response and breach-notification policy**

- Define a formal response plan.
- Establish escalation and decision authority.
- Define evidence-preservation requirements.
- Establish regulator and stakeholder contact procedures.
- Prepare approved communication templates.

### Short term — 1 to 3 months

**Establish cloud-security controls**

- Strengthen IAM and access reviews.
- Encrypt sensitive information at rest and in transit.
- Perform recurring cloud-configuration assessments.
- Improve logging, alerting, and monitoring.

**Assign accountable security leadership**

- Appoint a CISO or equivalent security leader.
- Define security, risk, and compliance responsibilities.
- Establish executive reporting and control ownership.

### Continuing program

- Maintain a formal risk register.
- Track compliance evidence and corrective actions.
- Review third-party and cloud-provider risks.
- Conduct recurring awareness training.
- Test the incident-response plan through exercises.
- Reassess risks after material changes and incidents.

## 4. Assessment Limitations

The assessment is based on a fictional, incomplete scenario rather than interviews, control testing, technical evidence, or access to a real environment. Ratings therefore demonstrate a GRC methodology rather than a certified conclusion about an operating company.
