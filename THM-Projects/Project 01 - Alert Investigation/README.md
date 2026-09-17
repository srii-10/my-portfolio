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
| Alert Case | Severity | Type | Verdict|
|-----------------|----------|------|--------|
| [Case 01 - Legitimate Employee Onboarding Email](./Case-01-Legitimate-Employee-Onboarding-Email.md) | Medium | Phishing | FP |
| [Case 02 - URL Shortening Sent by a Suspicious Sender](./) | Medium | Phishing | TP |
| [Case 03 - Blacklisted External URL Blocked by Firewall](./) | High | Firewall | TP |
| [Case 04 - Spoofed Domain Sending Suspicious URL](./) | Medium | Phishing | TP |
