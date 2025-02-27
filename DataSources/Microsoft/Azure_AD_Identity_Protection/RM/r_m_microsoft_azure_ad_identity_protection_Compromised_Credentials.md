Vendor: Microsoft
=================
### Product: [Azure AD Identity Protection](../ds_microsoft_azure_ad_identity_protection.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   8   |   4    |     6      |      1      |    1    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| remote-access | <b>T1550 - Use Alternate Authentication Material</b><br> ↳ <b>RLA-UAPackage-F</b>: First time usage of Windows authentication package<br> ↳ <b>RLA-UAPackage-A</b>: Abnormal usage of Windows authentication package<br><br><b>T1021 - Remote Services</b><br> ↳ <b>RA-GH-A</b>: Abnormal access to asset for group<br> ↳ <b>RA-GH-F</b>: First access to asset for group<br> ↳ <b>RA-UH-A</b>: Abnormal access to asset<br> ↳ <b>RA-UH-F</b>: First access to asset<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>RA-GH-A</b>: Abnormal access to asset for group<br> ↳ <b>RA-GH-F</b>: First access to asset for group<br> ↳ <b>RA-UH-A</b>: Abnormal access to asset<br> ↳ <b>RA-UH-F</b>: First access to asset<br><br><b>T1078.002 - T1078.002</b><br> ↳ <b>SL-UH-A</b>: Abnormal access from asset for a service account<br><br><b>T1550.003 - Use Alternate Authentication Material: Pass the Ticket</b><br> ↳ <b>EXPERT-PENTEST-DOMAINS</b>: Possible credentials theft attack detected<br><br><b>T1558 - Steal or Forge Kerberos Tickets</b><br> ↳ <b>EXPERT-PENTEST-DOMAINS</b>: Possible credentials theft attack detected |  • <b>RLA-UAPackage</b>: Windows authentication packages used when connecting to remote hosts<br> • <b>RA-UH</b>: Assets accessed by this user remotely<br> • <b>RA-GH</b>: Assets accessed by this peer group remotely<br> • <b>AL-UsH</b>: Source hosts per User |