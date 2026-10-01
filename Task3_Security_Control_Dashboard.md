# Task 3: Security Control Dashboard and Management Reporting

## Organisation: Meridian Digital Services (MDS)

## 3.1 Purpose

The Security Control Monitoring Dashboard provides senior management and the Board with a concise view of the effectiveness of key security controls.

The dashboard uses KPIs and KRIs from the Continuous Control Monitoring Register and presents the target, current result, trend, RAG status and required management action.

The figures used in this dashboard are illustrative because the MDS scenario does not provide actual operational monitoring data.

---

## 3.2 Security Control Monitoring Dashboard

| Metric | Owner | Target | Current | Trend | RAG | Management Action |
|---|---|---:|---:|---|---|---|
| MFA Coverage | IAM Manager | ≥98% | 97% | ↑ Improving | Amber | Complete MFA rollout for remaining users |
| Critical Vulnerabilities Remediated Within SLA | Infrastructure Manager | ≥95% | 88% | ↓ Declining | Red | Prioritise overdue critical vulnerabilities |
| EDR Endpoint Coverage | Endpoint Manager | ≥98% | 99% | → Stable | Green | Continue monitoring endpoint health |
| Critical SIEM Log Sources Ingesting | SOC Manager | ≥98% | 96% | ↓ Declining | Amber | Investigate missing or delayed log sources |
| Backup Success Rate | Infrastructure Manager | ≥98% | 99% | → Stable | Green | Continue daily monitoring and restore testing |
| Critical Systems Patch Compliance | Infrastructure Manager | ≥95% | 93% | ↓ Declining | Amber | Prioritise systems outside patch SLA |
| Security Awareness Completion | HR / Security Awareness Lead | ≥95% | 94% | ↑ Improving | Amber | Follow up with outstanding employees |
| Critical Cloud Findings Remediated Within SLA | Cloud Security Manager | ≥95% | 91% | ↓ Declining | Amber | Prioritise critical cloud misconfigurations |
| Privileged Access Reviews Completed | IAM Manager | ≥98% | 99% | → Stable | Green | Continue monthly access reviews |
| Critical Suppliers Reviewed | Vendor Management | 100% annually | 96% | ↑ Improving | Amber | Complete outstanding supplier assessments |

---

## 3.3 RAG Classification

### Green

Performance is within the approved target or tolerance. Routine monitoring continues.

### Amber

Performance is approaching or has moderately exceeded the defined tolerance. The control owner should investigate the cause and implement corrective action where necessary.

### Red

Performance has materially breached the approved threshold or indicates a significant control weakness. Management escalation and corrective action are required.

---

## 3.4 Operational and Executive Escalation

Not every dashboard exception requires Board attention. Escalation should be based on severity, persistence, business impact and risk exposure.

### Operational Escalation

The following may normally be managed at operational level:

- Minor decline in control performance.
- Isolated endpoint or logging issues.
- Individual overdue remediation items.
- Small number of incomplete training records.

The control owner should investigate and correct the issue.

### Executive Escalation

The following should normally receive executive attention:

- Critical vulnerabilities outside the approved SLA.
- Significant decline in patch compliance.
- Major gaps in SIEM visibility.
- Repeated control failures.
- Significant cloud-security exposure.
- Control performance remaining below target across multiple reporting periods.

The CISO and relevant senior management should review the issue and agree corrective actions.

### Board Attention

Board-level reporting should focus on material and persistent risks, including:

- Significant exposure to critical vulnerabilities.
- Material security incidents.
- Persistent control failures.
- Significant deterioration in overall security posture.
- Risks exceeding organisational risk appetite.
- Major regulatory, financial or business impacts.

---

## 3.5 Trend-Based Observations

### Observation 1: Vulnerability Remediation

Critical vulnerability remediation is currently at 88%, below the 95% target, with a declining trend.

This indicates that remediation performance requires management attention. The organisation should prioritise overdue critical vulnerabilities, particularly those affecting internet-facing or business-critical systems.

### Observation 2: SIEM Visibility

Critical SIEM log-source coverage is at 96%, below the 98% target and showing a declining trend.

This may reduce the organisation's ability to detect and investigate security events. The SOC should identify missing or unreliable log sources and restore monitoring coverage.

### Observation 3: Security Awareness

Security-awareness completion is at 94%, slightly below the 95% target but showing an improving trend.

Management should follow up with outstanding employees while continuing the existing awareness programme.

---

## 3.6 Management Report

### Overall Control Effectiveness

The dashboard indicates that several MDS controls are operating within their defined targets, particularly EDR coverage, backup success and privileged-access reviews.

However, several controls are below target, including vulnerability remediation, SIEM log-source coverage, patch compliance, security-awareness completion and cloud-security remediation.

The most significant concern is the performance of critical vulnerability remediation, which is below the approved target and has a declining trend.

### Three Highest-Priority Concerns

#### 1. Critical Vulnerability Remediation

Current performance is 88% against a 95% target.

**Management action:** Prioritise overdue critical vulnerabilities and require regular reporting until performance returns to the approved target.

#### 2. SIEM Log Visibility

Critical log-source ingestion is 96% against a 98% target.

**Management action:** Identify missing or unreliable log sources and restore complete monitoring coverage.

#### 3. Patch and Cloud Security Compliance

Patch compliance is 93% and critical cloud findings remediation is 91%, both below the 95% target.

**Management action:** Review the causes of delayed remediation, assign accountable owners and monitor progress through the security governance process.

---

## 3.7 Recommended Management Actions

| Priority | Action | Owner | Expected Outcome |
|---|---|---|---|
| High | Reduce overdue critical vulnerabilities | Infrastructure Manager | Vulnerability remediation returns to ≥95% |
| High | Restore missing SIEM log sources | SOC Manager | Critical logging coverage reaches ≥98% |
| High | Improve patch and cloud remediation | Infrastructure / Cloud Security Managers | Security exposure reduced and SLA compliance improved |
| Medium | Complete outstanding awareness training | HR / Security Awareness Lead | Completion reaches ≥95% |
| Medium | Complete outstanding supplier reviews | Vendor Management | Critical supplier assurance reaches 100% |

---

## 3.8 Dashboard Reporting Principles

The dashboard should be reviewed regularly and should focus on information that supports management decisions.

Management reporting should:

- Show performance against defined targets.
- Highlight trends rather than only current values.
- Identify persistent control weaknesses.
- Link exceptions to accountable owners.
- Distinguish operational issues from material risks.
- Track corrective actions to completion.
- Escalate significant risks through established governance channels.

---

## 3.9 Expected Outcome

The dashboard provides management with a concise view of control effectiveness and highlights areas requiring corrective action or escalation.

By combining current performance, targets, trends and RAG status, MDS can move from simply reporting security data to using monitoring information to support risk-based management decisions.
