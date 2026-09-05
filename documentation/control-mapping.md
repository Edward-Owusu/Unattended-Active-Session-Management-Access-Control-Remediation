# Control Mapping --- Unattended Active Session Management

## Control Objective

Prevent unauthorized access to corporate information and systems when an
authenticated workstation is left unattended.

  ---------------------------------------------------------------------------------------
  Control ID   Control         GDPR        HIPAA                 PCI DSS     Control Type
  ------------ --------------- ----------- --------------------- ----------- ------------
  CTRL-003.1   Enforce maximum Art. 32     45 CFR                Req. 8      Preventive
               15-minute                   §164.310(a)(2)(iii)               
               automatic                                                     
               screen lock                                                   

  CTRL-003.2   Require manual  Art. 32     45 CFR §164.310       Req. 8      Preventive
               lock before                                                   
               leaving                                                       
               workspace                                                     

  CTRL-003.3   Monitor         Art. 32     Security safeguards   Req. 8      Detective
               endpoint                                                      
               timeout                                                       
               configuration                                                 
               centrally                                                     

  CTRL-003.4   Conduct         Art. 32     Workstation security  Req. 9      Detective
               physical                                                      
               compliance                                                    
               inspections                                                   

  CTRL-003.5   Security        Art. 32     Workforce security    Req. 12     Corrective /
               awareness and                                                 Preventive
               exception                                                     
               management                                                    
  ---------------------------------------------------------------------------------------

## Control Design Rationale

The control set uses both technical enforcement and governance.
Technical enforcement reduces dependence on user behavior, while
training and inspection address recurring exceptions and accountability.

## Validation Notes

Framework references are presented as practical portfolio mappings
rather than legal advice or a certification statement. The applicable
compliance obligations must be confirmed for the target organization.
