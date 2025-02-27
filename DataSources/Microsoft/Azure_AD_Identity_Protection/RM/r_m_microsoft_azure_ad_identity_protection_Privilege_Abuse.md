Vendor: Microsoft
=================
### Product: [Azure AD Identity Protection](../ds_microsoft_azure_ad_identity_protection.md)
### Use-Case: [Privilege Abuse](../../../../UseCases/uc_privilege_abuse.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   3    |     3      |      1      |    1    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| remote-access | <b>T1078 - Valid Accounts</b><br> ↳ <b>RA-UH-CS-NC</b>: Remote access  to a critical system for user with no information<br> ↳ <b>RA-F-F-CS</b>: First remote access to critical system for user<br> ↳ <b>RA-F-A-CS</b>: Abnormal remote access to critical system for user<br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset<br> ↳ <b>DC18-new</b>: Account switch by new user<br><br><b>T1021 - Remote Services</b><br> ↳ <b>RA-UH-CS-NC</b>: Remote access  to a critical system for user with no information<br> ↳ <b>RA-F-F-CS</b>: First remote access to critical system for user<br> ↳ <b>RA-F-A-CS</b>: Abnormal remote access to critical system for user<br> ↳ <b>RA-HT-EXEC-new</b>: New user remote access to executive asset<br><br><b>T1078.002 - T1078.002</b><br> ↳ <b>SL-UH-A</b>: Abnormal access from asset for a service account |  • <b>AL-HT-EXEC</b>: Executive Assets<br> • <b>RA-UH</b>: Assets accessed by this user remotely<br> • <b>AL-UsH</b>: Source hosts per User |