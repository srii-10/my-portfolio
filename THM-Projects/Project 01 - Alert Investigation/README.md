## Project 01 - Alert Investigation

### Objectives
- Analyze affected entities and attack indicators
- Determine whether an alert should be classified as True Positive or False Positive
- Assess whether escalation is necessary
- Explain the rationale behind classification and escalation decisions
- Provide appropriate recommendations for remediation

### Environment
TryHackMe Cloud-Based SOC Simulator: “Introduction to Phishing”.

### Skills
- Evidence Analysis
- IOC Analysis
- Alert Triage
- Alert Classification
- Alert Reporting
- Alert Escalation

### Cases
| Alert Rule Case | Severity | Type | Verdict|
|-----------------|----------|------|--------|
| Case 01 - Inbound Email Containing Suspicious External Link | Medium | Phishing | FP |
| Case 02 - Inbound Email Containing Suspicious External Link | Medium | Phishing | TP |
| Case 03 - Access to Blacklisted External URL Blocked by Firewall | High | Firewall | TP |
| Case 04 - Inbound Email Containing Suspicious External Link | Medium | Phishing | TP |
