# Detailed Risk and Compliance Assessment

## Scenario

NoorPay is a fictional Saudi fintech company providing digital-payment and e-wallet services. The scenario assumes sensitive financial information, cloud infrastructure, informal governance, an undocumented prior breach, and preparation for regulatory review.

## Assessment Method

Risks are evaluated qualitatively using likelihood and impact on a five-level scale. The resulting rating supports prioritization; it does not replace a technical audit or quantitative financial analysis.

## Risk Register

| ID | Risk | Primary assets | Threat source | Likelihood | Impact | Priority |
| --- | --- | --- | --- | --- | --- | --- |
| R.01 | Unauthorized access caused by weak cloud controls | Customer data and cloud services | External attacker | High | Very high | Very high |
| R.02 | No formal risk-management process | Governance processes | Internal mismanagement | High | High | High |
| R.03 | GDPR and PDPL non-compliance | Customer data | Regulatory exposure | High | Very high | Very high |
| R.04 | Undocumented breach enables repeated weaknesses | Incident response and customer data | External attacker | High | Very high | Very high |
| R.05 | Weak access governance and missing security leadership | Identity and access systems | External or insider threat | High | High | High |
| R.06 | Cloud misconfiguration exposes data | Cloud infrastructure | External attacker | High | Very high | Very high |
| R.07 | Human error caused by insufficient awareness | Employee accounts | Phishing or social engineering | High | High | High |
| R.08 | Missing formal cloud-security policy | Cloud infrastructure | External attacker | High | High | High |

## Compliance Gap Themes

### GDPR

- Data protection by design
- Security of processing
- Breach notification
- Accountability and evidence
- Access control and authentication
- Data minimization

### Saudi PDPL

- Personal-data protection controls
- Breach-notification governance
- Processing accountability
- Consent and data handling
- Retention governance
- Third-party and cloud-provider oversight

The academic scenario identifies gaps because policies, technical evidence, ownership, and incident documentation are absent or incomplete. Regulatory requirements can change; current obligations should always be verified with qualified legal and compliance professionals.

## Remediation Roadmap

### Immediate

- Approve an incident-response and breach-notification policy.
- Define decision authority and escalation paths.
- Preserve evidence and establish regulatory contact procedures.

### Short term

- Strengthen IAM, encryption, monitoring, and cloud configuration reviews.
- Assign a CISO or equivalent accountable security leader.
- Establish a formal risk register and control-ownership model.

### Continuing

- Review third-party risks.
- Test incident procedures.
- Track compliance evidence and corrective actions.
- Deliver recurring security-awareness training.
