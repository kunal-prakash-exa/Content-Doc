Vendor: Cisco
=============
### Product: [Proxy Umbrella](../ds_cisco_proxy_umbrella.md)
### Use-Case: [Data Leak](../../../../UseCases/uc_data_leak.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  12   |   4    |     6      |      3      |    3    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| app-activity         | <b>T1114.003 - Email Collection: Email Forwarding Rule</b><br> ↳ <b>EM-InRule-EX</b>: User has created an inbox forwarding rule to forward email to an external domain email<br> ↳ <b>EM-InRule-Public</b>: User has created an inbox forwarding rule to forward email to a public email domain<br> ↳ <b>EM-InRule-Fin</b>: User has created an inbox forwarding rule to forward emails containing financial keywords    |    |
| print-activity       | <b>T1052 - Exfiltration Over Physical Medium</b><br> ↳ <b>PR-UP-F</b>: First print activity from printer for user<br> ↳ <b>PR-UP-A</b>: Abnormal printer for user<br> ↳ <b>PR-UT-TOW</b>: Abnormal print activity time for user<br> ↳ <b>PR-SRC-CODE</b>: Printed document with source code file extension    |  • <b>PR-UT-TOW</b>: Print activity time for user<br> • <b>PR-UP</b>: Printers for user    |
| web-activity-allowed | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-New-File-20</b>: User with no web activity history has uploaded 20MB or more<br><br><b>T1567.002 - Exfiltration Over Web Service: Exfiltration to Cloud Storage</b><br> ↳ <b>WEB-FS</b>: User has accessed a file sharing domain<br> ↳ <b>WEB-OU-FS</b>: One of the top file sharing users in the organization<br> ↳ <b>WEB-OG-FS</b>: One of the top file sharing users in the peer group<br><br><b>T1041 - Exfiltration Over C2 Channel</b><br> ↳ <b>A-WEB-EXFIL-ASSET</b>: Large amount of data exfiltrated from host<br><br><b>T1567 - Exfiltration Over Web Service</b><br> ↳ <b>A-WEB-EXFIL-ASSET</b>: Large amount of data exfiltrated from host |  • <b>WEB-OG-FS</b>: File sharing activities of users in the peer group<br> • <b>WEB-OU-FS</b>: File sharing activities of users in the organization |