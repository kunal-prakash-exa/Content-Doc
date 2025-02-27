Vendor: Fortinet
================
### Product: [Fortinet FortiWeb](../ds_fortinet_fortinet_fortiweb.md)
### Use-Case: [Data Leak](../../../../UseCases/uc_data_leak.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   8   |   4    |     5      |      2      |    2    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| dlp-email-alert-out-failed | <b>T1048.003 - Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol</b><br> ↳ <b>FEM-UD-R</b>: Repeated email failure to domain<br> ↳ <b>FEM-FU</b>: Emailing a previously failed attachment<br> ↳ <b>EM-BSum-5MB-Fail</b>: Failed attempt to email over 5MB of data to a personal email domain.    |  • <b>FEM-FU</b>: Users per file names in failed outgoing emails<br> • <b>FEM-UD</b>: Failed Email Domains per User    |
| web-activity-allowed       | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-New-File-20</b>: User with no web activity history has uploaded 20MB or more<br><br><b>T1567.002 - Exfiltration Over Web Service: Exfiltration to Cloud Storage</b><br> ↳ <b>WEB-FS</b>: User has accessed a file sharing domain<br> ↳ <b>WEB-OU-FS</b>: One of the top file sharing users in the organization<br> ↳ <b>WEB-OG-FS</b>: One of the top file sharing users in the peer group<br><br><b>T1041 - Exfiltration Over C2 Channel</b><br> ↳ <b>A-WEB-EXFIL-ASSET</b>: Large amount of data exfiltrated from host<br><br><b>T1567 - Exfiltration Over Web Service</b><br> ↳ <b>A-WEB-EXFIL-ASSET</b>: Large amount of data exfiltrated from host |  • <b>WEB-OG-FS</b>: File sharing activities of users in the peer group<br> • <b>WEB-OU-FS</b>: File sharing activities of users in the organization |