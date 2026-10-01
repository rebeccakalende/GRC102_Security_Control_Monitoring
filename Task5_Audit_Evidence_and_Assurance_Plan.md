# Task 5 – Audit Evidence and Assurance Plan

## 5.1 Purpose

The purpose of this assurance plan is to validate that MDS security-control monitoring evidence is sufficient, relevant, reliable and traceable for management and audit purposes.

---

## 5.2 Audit Evidence Standard / Checklist

MDS security-control evidence should meet the following requirements:

| Evidence Criterion | Requirement | Assurance Check |
|---|---|---|
| Sufficient | Evidence is adequate to support the control conclusion | Is there enough evidence to demonstrate that the control operated? |
| Relevant | Evidence directly relates to the control, risk and review period | Does the evidence support the specific control being assessed? |
| Reliable | Evidence comes from a trusted source and has appropriate integrity | Is the source authoritative and protected from unauthorised alteration? |
| Traceable | Evidence can be linked to the control, system, owner and period tested | Can the evidence be traced from the control register to the original source? |
| Complete | Required evidence and exceptions are included | Are there missing periods, systems or exceptions? |
| Timely | Evidence relates to the required monitoring period | Was the evidence generated or captured within the relevant period? |
| Authentic | Evidence can be attributed to its originating system or owner | Can its source and ownership be verified? |
| Protected | Evidence is stored securely with appropriate access restrictions | Is access limited and is unauthorised modification prevented? |

### Evidence Checklist

Before evidence is accepted for assurance, the reviewer should confirm:

- [ ] Evidence supports the stated control objective.
- [ ] Evidence covers the relevant control period.
- [ ] Evidence source is identified.
- [ ] Control owner and monitoring owner are identifiable.
- [ ] Evidence is complete and readable.
- [ ] Evidence has not been unauthorisedly altered.
- [ ] Exceptions and failures are included.
- [ ] Evidence can be traced to the original system or record.
- [ ] Evidence is retained according to MDS requirements.
- [ ] Evidence supports the assurance conclusion.

---

## 5.3 Sampling vs Complete-Population Testing

Sampling may be appropriate where:

- The control operates across a large population.
- Testing the complete population would not be proportionate.
- The population is sufficiently consistent for a representative sample.
- The risk and control objective can be assessed through selected items.
- The sample can be documented and justified.

Examples include:

- Sampling user access reviews.
- Sampling security-awareness records.
- Sampling change-management tickets.
- Sampling supplier assurance records.

Complete-population testing is preferable where:

- The population is small enough to test completely.
- Automated data is available and reliable.
- The control involves critical or high-risk events.
- Every exception is important to the control conclusion.
- The control objective requires complete coverage.

Examples include:

- Critical vulnerabilities identified during the reporting period.
- Critical SIEM log-source coverage.
- Failed backups for business-critical systems.
- Privileged accounts where the population is manageable.
- Critical security exceptions.

The testing approach should be documented so that management and audit can understand why sampling or complete-population testing was selected.

---

## 5.4 Evidence Retention and Protection

MDS should retain assurance evidence in a controlled repository with appropriate access restrictions.

Evidence should:

- Be linked to the relevant control ID.
- Identify the monitoring or testing period.
- Include the evidence source and date.
- Identify the responsible control owner.
- Be protected against unauthorised alteration or deletion.
- Have access restricted according to business need.
- Be retained according to applicable MDS retention requirements.
- Preserve the original evidence where practical.
- Maintain a clear relationship between evidence, findings and remediation records.

Evidence should also be linked to the control period so that reviewers can establish exactly which period the evidence supports.

---

## 5.5 Independence of Assurance

Control operation and control assurance should be separated where practical.

### Control Operator

Responsible for:

- Operating the security control.
- Monitoring control performance.
- Maintaining operational evidence.
- Addressing control failures.

### Assurance Reviewer

Responsible for:

- Reviewing the evidence.
- Testing whether the control operated effectively.
- Challenging exceptions and unsupported conclusions.
- Performing independent retesting where required.
- Reporting assurance results to management.

The person performing assurance should not approve their own control operation or independently close a deficiency they were responsible for remediating.

Where full organisational independence is not practical, MDS should apply compensating measures such as secondary review, management oversight or periodic independent assessment.

---

# 5.6 90-Day Control Assurance Calendar

| Period | Assurance Activity | Priority | Output / Reporting |
|---|---|---|---|
| Days 1–15 | Review critical vulnerability remediation and SLA performance | High | Vulnerability assurance report |
| Days 1–15 | Validate MFA and privileged-access monitoring evidence | High | Access-control assurance findings |
| Days 16–30 | Review SIEM log-source coverage and security alert evidence | High | Logging assurance report |
| Days 16–30 | Review endpoint/EDR monitoring evidence | High | EDR assurance findings |
| Days 31–45 | Review backup success and restoration-testing evidence | High | Backup assurance report |
| Days 31–45 | Review critical-system patch compliance | High | Patch assurance findings |
| Days 46–60 | Review change-management and emergency-change evidence | Medium | Change-control assurance report |
| Days 46–60 | Review cloud security posture monitoring | High | Cloud-control findings |
| Days 61–75 | Review security-awareness and phishing-resilience evidence | Medium | Awareness assurance report |
| Days 61–75 | Review third-party security assurance evidence | Medium | Supplier assurance findings |
| Days 76–85 | Follow up open deficiencies and overdue remediation | High | Remediation follow-up report |
| Days 86–90 | Consolidate assurance results and perform management review | High | Executive assurance report |

### Reporting Points

**Day 30:** Initial assurance findings reported to Security Governance and relevant control owners.

**Day 60:** Mid-cycle assurance status reported to senior management, including overdue deficiencies.

**Day 90:** Consolidated assurance report presented to senior management and relevant Board/risk oversight structures.

---

# 5.7 Follow-Up and Escalation

Open deficiencies identified during assurance should be:

1. Assigned to an accountable control owner.
2. Given a documented remediation action.
3. Assigned a target completion date.
4. Monitored through the control monitoring register.
5. Escalated when overdue or when risk exceeds the defined tolerance.
6. Independently retested after remediation.
7. Formally closed only when sufficient evidence supports closure.

---

# 5.8 Final Executive Summary

## Overall Assurance Position

MDS should maintain continuous assurance over security controls by combining monitoring evidence, automated security telemetry, management review and independent assurance activities.

The assurance process should focus on whether controls are operating effectively, whether exceptions are identified promptly, and whether remediation is completed and independently retested.

## Top Monitoring Priorities

1. **Critical vulnerability remediation**  
   Monitor critical vulnerabilities against the defined SLA, with particular attention to overdue and internet-facing vulnerabilities.

2. **Security visibility and monitoring**  
   Maintain reliable SIEM, endpoint, identity and cloud telemetry so that security events and control exceptions can be detected and evidenced.

3. **Access and identity controls**  
   Maintain effective MFA coverage and regular privileged-access reviews to reduce identity-related security risk.

4. **Backup, patching and recovery controls**  
   Monitor backup success, restoration testing and critical-system patch compliance.

5. **Control exceptions and remediation**  
   Ensure control failures are assigned, escalated, remediated and independently retested before closure.

## First Three Improvements Management Should Implement

### Improvement 1 – Strengthen Critical Vulnerability Remediation

Establish tighter monitoring and escalation for critical vulnerabilities, prioritising overdue and internet-facing vulnerabilities and ensuring remediation delays are formally risk-assessed.

### Improvement 2 – Improve Evidence Quality and Traceability

Standardise how monitoring evidence is collected, retained, protected and linked to control IDs, owners and reporting periods.

### Improvement 3 – Strengthen Independent Assurance and Follow-Up

Introduce a structured assurance cycle with independent retesting of significant control failures and formal management reporting of overdue remediation.

---

## 5.9 Expected Outcome

The assurance plan provides MDS with a structured approach for validating that security-control evidence is reliable and suitable for management and audit purposes.

It also establishes a 90-day cycle for priority reviews, reporting, follow-up and independent assurance.
