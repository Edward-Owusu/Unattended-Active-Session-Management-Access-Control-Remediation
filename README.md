# Unattended Active Session Management --- GRC / IT Audit Project

A portfolio-ready GRC/IT Audit case study focused on the risk of
employees leaving corporate workstations logged in and unattended.

## Project Overview

This project demonstrates an end-to-end GRC lifecycle:

**Risk Identification → Risk Assessment → Framework Mapping → Control
Design → Audit Testing → Evidence → Metrics → Remediation → Policy**

## Key Risk

**Risk ID:** RSK-003

Employees may leave active corporate endpoints unlocked while
unattended, creating opportunities for unauthorized physical access,
misuse of authenticated sessions, data exposure, and further
unauthorized activity.

### Risk Scoring

-   Inherent Likelihood: **4/5**
-   Inherent Impact: **4/5**
-   Inherent Risk: **16/25**
-   Residual Likelihood: **1/5**
-   Residual Impact: **4/5**
-   Residual Risk: **4/25**
-   Modeled risk-score reduction: **75%**

## Framework References

The case study uses practical mappings to: - GDPR Article 32 ---
Security of Processing - HIPAA workstation-security safeguards - PCI DSS
v4.0 session/access control requirements

Mappings should be validated against the applicable organization's exact
scope and control environment.

## Proposed Controls

1.  Centralized 15-minute idle-timeout enforcement through GPO/MDM.
2.  Mandatory manual screen locking before leaving a workstation.
3.  Endpoint compliance telemetry and configuration monitoring.
4.  Unannounced physical/remote compliance inspections.
5.  Security awareness training and exception management.

## Audit Testing

-   **AUD-004.1:** Unattended endpoint inspection --- monthly --- target
    0 exceptions.
-   **AUD-004.2:** Timeout configuration validation --- quarterly ---
    target 100% compliance.
-   **AUD-004.3:** Security awareness validation --- annually --- target
    100% completion.

## Repository Structure

``` text
Unattended-Active-Session-Management-GRC-Project/
├── README.md
├── .gitignore
├── data/
│   └── Unattended_Active_Session_Management_GRC_Project.xlsx
└── documentation/
    ├── risk-assessment.md
    ├── control-mapping.md
    ├── audit-testing.md
    ├── remediation-plan.md
    └── unattended-session-security-policy.md
```

## Skills Demonstrated

GRC \| IT Audit \| IT Risk \| Risk Assessment \| Control Design \|
Compliance \| Control Testing \| Evidence Collection \| Security Metrics
\| Policy Development \| Risk Remediation

## Disclaimer

This is a sanitized educational portfolio case study. It does not
contain confidential organizational information, credentials, production
configurations, or real security-event data.
