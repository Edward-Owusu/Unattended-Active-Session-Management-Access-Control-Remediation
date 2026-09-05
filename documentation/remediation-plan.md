# Remediation Plan --- Unattended Active Session Management

## Remediation Objective

Reduce the likelihood of unauthorized physical access to active
authenticated sessions and establish measurable, repeatable control
enforcement.

  ------------------------------------------------------------------------------
  Action         Owner          Priority       Target State   Validation
  -------------- -------------- -------------- -------------- ------------------
  Configure      Endpoint       High           100% managed   GPO/MDM evidence
  15-minute idle Engineering                   endpoints      
  timeout                                                     

  Enable         IT Security    High           Daily          Dashboard/export
  centralized                                  compliance     
  compliance                                   visibility     
  telemetry                                                   

  Implement      Security       Medium         100% workforce LMS report
  manual-lock    Awareness                     trained        
  awareness                                                   
  campaign                                                    

  Launch         Physical/IT    Medium         Monthly        Inspection logs
  unannounced    Security                      testing        
  inspections                                                 

  Establish      GRC            Medium         All exceptions Exception register
  exception                                    documented     
  process                                                     

  Track repeat   Security       Low            Escalation     Case/ticket
  violations     Operations /                  workflow       evidence
                 HR                            active         
  ------------------------------------------------------------------------------

## Implementation Phases

### Phase 1 --- Baseline

Inventory managed endpoints and measure current timeout compliance.

### Phase 2 --- Enforce

Deploy the approved idle-timeout policy through centralized endpoint
management.

### Phase 3 --- Monitor

Create dashboards for configuration compliance and observed exceptions.

### Phase 4 --- Test

Perform monthly/quarterly/annual control testing according to the audit
plan.

### Phase 5 --- Sustain

Review metrics, exceptions, training, and repeat findings with control
owners.

## Success Metrics

-   100% endpoint timeout compliance
-   0 unattended unlocked endpoints during inspections
-   100% annual training completion
-   100% documented exceptions
-   100% remediation of confirmed findings within the approved SLA
