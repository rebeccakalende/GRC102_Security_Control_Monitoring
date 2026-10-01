# Task 1: Continuous Control Monitoring Register

## Organisation: Meridian Digital Services (MDS)

## 1.1 Purpose

The Continuous Control Monitoring Register establishes a structured approach for monitoring key security controls across Meridian Digital Services' hybrid technology environment.

The register identifies control ownership, monitoring responsibilities, evidence sources, monitoring frequency, performance measures, thresholds, escalation requirements and evidence-retention expectations.

The selected controls provide coverage across identity, endpoints, infrastructure, data, cloud services, third-party services and security awareness.

---

## 1.2 Continuous Control Monitoring Register

| ID | Security Control | Control Objective and Risk Addressed | Control Owner | Monitoring Owner | Primary Evidence Source | Frequency | KPI/KRI | Target / Threshold | Escalation Trigger | Evidence Retention | RAG |
|---|---|---|---|---|---|---|---|---|---|---|---|
| CCM-01 | Identity & Privileged Access Reviews | Ensure access remains appropriate and excessive privileges are removed. | IAM Manager | Security Governance / IAM Analyst | IAM reports, access review records, privileged-access logs | Monthly | % of privileged accounts reviewed | ≥98% | <95% or unidentified privileged account → CISO | 12 months | Green |
| CCM-02 | Multi-Factor Authentication Coverage | Reduce risk of unauthorised access to corporate and cloud services. | IAM Manager | Security Operations | Identity platform reports, MFA dashboard, authentication logs | Weekly | % of in-scope accounts protected by MFA | ≥98% | <95% → CISO and IT Manager | 12 months | Green |
| CCM-03 | Vulnerability Identification & Remediation | Ensure vulnerabilities are identified and remediated within approved SLAs. | Infrastructure Manager | Vulnerability Management Lead | Vulnerability scanner reports, remediation tickets | Weekly | % of critical vulnerabilities remediated within SLA | ≥95% | <90% or critical internet-facing vulnerability overdue → CISO | 24 months | Amber |
| CCM-04 | Endpoint Protection / EDR | Ensure corporate endpoints are protected and reporting correctly. | Endpoint Manager | Security Operations | EDR dashboard, endpoint health reports, alert logs | Daily | % of active endpoints reporting to EDR | ≥98% | <95% or critical endpoint without protection → CISO | 12 months | Green |
| CCM-05 | Security Logging & SIEM Ingestion | Ensure security-relevant events are available for detection and investigation. | SOC Manager | SIEM Analyst | SIEM dashboards, log-source health reports, ingestion alerts | Daily | % of critical log sources successfully ingesting | ≥98% | <95% or critical log source offline → SOC Manager/CISO | 12 months | Green |
| CCM-06 | Backup Success & Restoration Testing | Ensure critical information can be recovered following failure or cyber incident. | Infrastructure Manager | IT Operations / Business Continuity | Backup reports, restore-test evidence, recovery logs | Daily / Quarterly Testing | Backup success rate and restore-test success | ≥98% backup success; 100% scheduled restore tests | Failed critical backup or failed restore test → CISO / IT Director | 24 months | Green |
| CCM-07 | Security Patch Compliance | Reduce exposure caused by unpatched systems. | Infrastructure Manager | Endpoint / Systems Team | Patch-management dashboard, system reports | Weekly | % of critical systems patched within SLA | ≥95% | <90% or critical asset outside SLA → CISO | 24 months | Amber |
| CCM-08 | Change Management / Emergency Changes | Ensure security-impacting changes are authorised, tested and traceable. | IT Change Manager | IT Governance / Internal Control | Change tickets, approvals, emergency-change records | Monthly | % of changes with documented approval | ≥98% | Unauthorised high-risk change → IT Director / CISO | 12 months | Green |
| CCM-09 | Data Protection / Encryption | Protect sensitive data from unauthorised disclosure or inappropriate handling. | Data Protection Officer | Security / Compliance Team | Encryption reports, DLP alerts, data classification records | Monthly | % of sensitive systems meeting encryption requirements | ≥98% | Unencrypted critical data store → CISO / DPO | 24 months | Green |
| CCM-10 | Security Awareness & Phishing Resilience | Reduce human-related security risk through awareness and testing. | HR Manager | Security Awareness Lead | Training records, phishing simulation results, completion reports | Monthly / Quarterly | Training completion and phishing failure rate | ≥95% completion; phishing failure ≤5% | <90% completion or phishing failure >10% → CISO / HR | 12 months | Amber |
| CCM-11 | Cloud Security Posture | Identify and correct insecure cloud configurations. | Cloud Infrastructure Manager | Cloud Security Team | CSPM reports, cloud configuration logs, security alerts | Weekly | % of critical cloud misconfigurations remediated within SLA | ≥95% | Critical exposure or <90% SLA compliance → CISO | 24 months | Amber |
| CCM-12 | Third-Party Security Assurance | Ensure material suppliers maintain appropriate security controls. | Vendor Management Manager | Risk / Third-Party Assurance | Security assessments, certifications, vendor questionnaires, contracts | Quarterly | % of critical suppliers reviewed | 100% annually | Critical supplier without current assessment → CRO / CISO | Contract + 24 months | Green |

---

## 1.3 Why These Controls Provide Meaningful Assurance

The selected controls provide a balanced view of Meridian Digital Services' security posture by covering preventive, detective and corrective activities across identity, endpoints, infrastructure, data, cloud services, third parties and human behaviour.

The register combines technical telemetry, management records and assurance evidence to provide continuing visibility rather than relying on one-time control implementation.

Each control is linked to an owner, evidence source, monitoring frequency, performance measure, threshold and escalation path. This allows management to determine whether controls continue to operate within defined expectations and whether weaknesses require further action.

---

## 1.4 Control Effectiveness Approach

### Control Design Effectiveness

Control design effectiveness considers whether a control is appropriately designed to address the identified security risk.

### Control Implementation

Control implementation confirms that the designed control has actually been put into operation.

### Control Operating Effectiveness

Control operating effectiveness determines whether the implemented control continues to operate as intended over time based on reliable and relevant evidence.

For example, MDS may have an MFA policy and MFA configuration in place. This demonstrates control design and implementation. Continuous monitoring of MFA coverage and authentication data provides evidence of whether MFA continues to operate effectively across the required user population.

---

## 1.5 RAG Status

The RAG statuses in this register are illustrative baseline values because the scenario does not provide actual current MDS monitoring results.

- **Green:** Control performance is within the approved target or tolerance.
- **Amber:** Performance is approaching or has moderately exceeded the defined tolerance and requires management attention.
- **Red:** Performance has materially breached the threshold or indicates a significant control failure requiring escalation.

---

## 1.6 Expected Outcome

The Continuous Control Monitoring Register provides MDS with a consistent mechanism for monitoring control performance, identifying exceptions, assigning accountability and escalating control weaknesses.

It supports management and Board assurance by linking security controls to measurable evidence, defined thresholds, responsible owners and documented escalation requirements.
