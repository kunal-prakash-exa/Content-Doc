Vendor: Ping Identity
=====================
### Product: [PingOne](../ds_ping_identity_pingone.md)
### Use-Case: [Privilege Abuse](../../../../UseCases/uc_privilege_abuse.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   3   |   1    |     2      |      4      |    4    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| app-login     | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application |    |
| service-logon | <b>T1078.002 - T1078.002</b><br> ↳ <b>SL-UH-A</b>: Abnormal access from asset for a service account    |  • <b>AL-UsH</b>: Source hosts per User |