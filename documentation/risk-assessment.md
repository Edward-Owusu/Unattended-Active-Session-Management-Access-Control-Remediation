# Risk Assessment --- Unattended Active Session Management

## Project Overview

This GRC/IT Audit case study assesses the risk created when employees
leave corporate workstations logged in and unattended during breaks,
lunch, meetings, or short periods away from their desks.

## Risk Statement

**Risk ID:** RSK-003

Employees may leave active corporate endpoints unlocked while
unattended. An unauthorized person could access applications, view or
modify sensitive information, misuse the employee's session, or use the
workstation as a stepping stone for further unauthorized activity.

## Risk Scoring

  Measure                 Score
  --------------------- -------
  Inherent Likelihood       4/5
  Inherent Impact           4/5
  Inherent Risk           16/25
  Residual Likelihood       1/5
  Residual Impact           4/5
  Residual Risk            4/25

The proposed control environment reduces the modeled risk from **16/25
to 4/25**, representing a 75% reduction in the numerical risk score.

## Risk Treatment

1.  Enforce centralized endpoint idle-timeout policies.
2.  Require users to manually lock screens before leaving workstations.
3.  Use automated compliance telemetry to identify policy exceptions.
4.  Conduct periodic physical and remote compliance checks.
5.  Provide recurring security-awareness training.
6.  Track exceptions and remediation to closure.

## Risk Acceptance

Any exception to the 15-minute timeout standard should be formally
documented, risk-assessed, approved by an authorized owner, and reviewed
periodically.

> This is a sanitized portfolio case study. Framework mappings and risk
> scores should be validated against the actual organization, technology
> environment, contractual obligations, and audit scope.
