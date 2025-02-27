Vendor: McAfee
==============
Product: McAfee Advanced Threat Defense
---------------------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   5    |     1      |      1      |    1    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  failed-physical-access<br> ↳[mcafee-hbss-dlp-alert](Ps/pC_mcafeehbssdlpalert.md)<br> ↳[mcafee-hbss-dlp-alert-2](Ps/pC_mcafeehbssdlpalert2.md)<br> | T1078 - Valid Accounts<br> | [<ul><li>1 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_mcafee_mcafee_advanced_threat_defense_Abnormal_Authentication_&_Access.md) |
|    [Physical Security](../../../UseCases/uc_physical_security.md)    |  failed-physical-access<br> ↳[mcafee-hbss-dlp-alert](Ps/pC_mcafeehbssdlpalert.md)<br> ↳[mcafee-hbss-dlp-alert-2](Ps/pC_mcafeehbssdlpalert2.md)<br> | T1078 - Valid Accounts<br> | [<ul><li>5 Rules</li></ul><ul><li>4 Models</li></ul>](RM/r_m_mcafee_mcafee_advanced_threat_defense_Physical_Security.md)    |
|    [Privileged Activity](../../../UseCases/uc_privileged_activity.md)    |  failed-physical-access<br> ↳[mcafee-hbss-dlp-alert](Ps/pC_mcafeehbssdlpalert.md)<br> ↳[mcafee-hbss-dlp-alert-2](Ps/pC_mcafeehbssdlpalert2.md)<br> | T1078 - Valid Accounts<br> | [<ul><li>1 Rules</li></ul>](RM/r_m_mcafee_mcafee_advanced_threat_defense_Privileged_Activity.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution | Persistence                                                         | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |