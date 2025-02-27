Vendor: Specops
===============
Product: Specops Password Reset
-------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  41   |   18   |     7      |      2      |    2    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-unlocked<br> ↳[specops-account-password-reset](Ps/pC_specopsaccountpasswordreset.md)<br><br> network-connection-successful<br> ↳[specops-account-unlocked](Ps/pC_specopsaccountunlocked.md)<br> | T1078 - Valid Accounts<br>    | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_specops_specops_password_reset_Abnormal_Authentication_&_Access.md) |
|    [Cryptomining](../../../UseCases/uc_cryptomining.md)    |  account-unlocked<br> ↳[specops-account-password-reset](Ps/pC_specopsaccountpasswordreset.md)<br><br> network-connection-successful<br> ↳[specops-account-unlocked](Ps/pC_specopsaccountunlocked.md)<br> | T1496 - Resource Hijacking<br>    | [<ul><li>1 Rules</li></ul>](RM/r_m_specops_specops_password_reset_Cryptomining.md)    |
|    [Lateral Movement](../../../UseCases/uc_lateral_movement.md)    |  account-unlocked<br> ↳[specops-account-password-reset](Ps/pC_specopsaccountpasswordreset.md)<br><br> network-connection-successful<br> ↳[specops-account-unlocked](Ps/pC_specopsaccountunlocked.md)<br> | T1071 - Application Layer Protocol<br>T1090.003 - Proxy: Multi-hop Proxy<br>T1190 - Exploit Public Fasing Application<br>TA0010 - TA0010<br>TA0011 - TA0011<br> | [<ul><li>39 Rules</li></ul><ul><li>17 Models</li></ul>](RM/r_m_specops_specops_password_reset_Lateral_Movement.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  account-unlocked<br> ↳[specops-account-password-reset](Ps/pC_specopsaccountpasswordreset.md)<br><br> network-connection-successful<br> ↳[specops-account-unlocked](Ps/pC_specopsaccountunlocked.md)<br> | TA0011 - TA0011<br>    | [<ul><li>3 Rules</li></ul>](RM/r_m_specops_specops_password_reset_Malware.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                                                                                                            | Execution | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control                                                                                                                                                                                                      | Exfiltration | Impact                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | ----------------------------------------------------------------------- |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Exploit Public Fasing Application](https://attack.mitre.org/techniques/T1190)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            | [Proxy: Multi-hop Proxy](https://attack.mitre.org/techniques/T1090/003)<br><br>[Application Layer Protocol](https://attack.mitre.org/techniques/T1071)<br><br>[Proxy](https://attack.mitre.org/techniques/T1090)<br><br> |              | [Resource Hijacking](https://attack.mitre.org/techniques/T1496)<br><br> |