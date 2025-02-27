Vendor: HashiCorp
=================
Product: HashiCorp Vault
------------------------
| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   3    |     3      |      2      |    2    |

|    Use-Case    | Event Types/Parsers    | MITRE TTP    | Content    |
|:----:| ---- | ---- | ---- |
| [Abnormal Authentication & Access](../../../UseCases/uc_abnormal_authentication_&_access.md) |  account-password-reset<br> ↳[hashicorp-app-login-2](Ps/pC_hashicorpapplogin2.md)<br> ↳[hashicorp-app-login-1](Ps/pC_hashicorpapplogin1.md)<br><br> privileged-object-access<br> ↳[hashicorp-password-reset](Ps/pC_hashicorppasswordreset.md)<br> | T1078 - Valid Accounts<br>       | [<ul><li>2 Rules</li></ul><ul><li>1 Models</li></ul>](RM/r_m_hashicorp_hashicorp_vault_Abnormal_Authentication_&_Access.md) |
|    [Account Manipulation](../../../UseCases/uc_account_manipulation.md)    |  account-password-reset<br> ↳[hashicorp-app-login-2](Ps/pC_hashicorpapplogin2.md)<br> ↳[hashicorp-app-login-1](Ps/pC_hashicorpapplogin1.md)<br><br> privileged-object-access<br> ↳[hashicorp-password-reset](Ps/pC_hashicorppasswordreset.md)<br> | T1098 - Account Manipulation<br> | [<ul><li>1 Rules</li></ul>](RM/r_m_hashicorp_hashicorp_vault_Account_Manipulation.md)    |
|    [Malware](../../../UseCases/uc_malware.md)    |  account-password-reset<br> ↳[hashicorp-app-login-2](Ps/pC_hashicorpapplogin2.md)<br> ↳[hashicorp-app-login-1](Ps/pC_hashicorpapplogin1.md)<br><br> privileged-object-access<br> ↳[hashicorp-password-reset](Ps/pC_hashicorppasswordreset.md)<br> | TA0002 - TA0002<br>    | [<ul><li>4 Rules</li></ul><ul><li>2 Models</li></ul>](RM/r_m_hashicorp_hashicorp_vault_Malware.md)    |
|    [Privilege Abuse](../../../UseCases/uc_privilege_abuse.md)    |  account-password-reset<br> ↳[hashicorp-app-login-2](Ps/pC_hashicorpapplogin2.md)<br> ↳[hashicorp-app-login-1](Ps/pC_hashicorpapplogin1.md)<br><br> privileged-object-access<br> ↳[hashicorp-password-reset](Ps/pC_hashicorppasswordreset.md)<br> | T1098 - Account Manipulation<br> | [<ul><li>1 Rules</li></ul>](RM/r_m_hashicorp_hashicorp_vault_Privilege_Abuse.md)    |

ATT&CK Matrix for Enterprise
----------------------------
| Initial Access                                                      | Execution | Persistence                                                                                                                                  | Privilege Escalation                                                | Defense Evasion                                                     | Credential Access | Discovery | Lateral Movement | Collection | Command and Control | Exfiltration | Impact |
| ------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------- | --------- | ---------------- | ---------- | ------------------- | ------------ | ------ |
| [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |           | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br>[Account Manipulation](https://attack.mitre.org/techniques/T1098)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> | [Valid Accounts](https://attack.mitre.org/techniques/T1078)<br><br> |                   |           |                  |            |                     |              |        |