Vendor: Symantec
================
### Product: [Symantec DLP](../ds_symantec_symantec_dlp.md)
### Use-Case: [Privileged Activity](../../../../UseCases/uc_privileged_activity.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  10   |   2    |     5      |     10      |   10    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| dlp-email-alert-in         | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| dlp-email-alert-out        | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| dlp-email-alert-out-failed | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| ds-access    | <b>T1207 - Rogue Domain Controller</b><br> ↳ <b>A-DS-DCShadow</b>: Possible DCShadow attack by asset detected.<br> ↳ <b>DS-DCShadow-E</b>: Possible DCShadow attack from Existing Machine<br> ↳ <b>DS-DCShadow-F</b>: First event for machine in possible DCShadow attack<br><br><b>T1484 - Group Policy Modification</b><br> ↳ <b>DS-UA</b>: First access to attribute for privileged user<br><br><b>T1003.006 - OS Credential Dumping: DCSync</b><br> ↳ <b>A-DCSync</b>: Possible DCSync Attack: New domain controller detected<br> ↳ <b>DCSync-ExistHost</b>: Possible DCSync attack - existing host has replicated Active Directory.<br> ↳ <b>DCSync-FirstDS</b>: Possible DCSync attack - first DS access event from host. |  • <b>DS-HOSTS</b>: Models hosts in an Active Directory environment<br> • <b>DS-UA</b>: Attributes per privileged user |
| failed-logon    | <b>T1078 - Valid Accounts</b><br> ↳ <b>SEQ-UH-12</b>: Logon attempt on a disabled account<br><br><b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive    |    |
| security-alert    | <b>T1068 - Exploitation for Privilege Escalation</b><br> ↳ <b>ALERT-EXEC</b>: Security violation by Executive    |    |