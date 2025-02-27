Vendor: Cisco
=============
### Product: [Meraki MX appliances](../ds_cisco_meraki_mx_appliances.md)
### Use-Case: [Data Exfiltration](../../../../UseCases/uc_data_exfiltration.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  10   |   6    |     6      |      6      |    6    |

| Event Type          | Rules    | Models    |
| ---- | ---- | ---- |
| vpn-logout          | <b>TA0010 - TA0010</b><br> ↳ <b>DLP-UPCOUNT</b>: Abnormal number of DLP policy violations for user<br> ↳ <b>DLP-GPCOUNT</b>: Abnormal number of DLP policy violations for peer group<br> ↳ <b>DLP-BSum</b>: Abnormal amount of data written during DLP policy violation<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>VPN-BSum</b>: Abnormal amount of data uploaded during VPN Session    |  • <b>DLP-BSum</b>: Sum of bytes written during DLP policy violation<br> • <b>DLP-GPCOUNT</b>: Count of DLP policy violations for peer group<br> • <b>DLP-UPCOUNT</b>: Count of DLP policy violations for user<br> • <b>VPN-BSum</b>: Sum of bytes uploaded during VPN |
| web-activity-denied | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>A-WEB-DynamicDNS</b>: Asset attempted access to a domain generated using Dynamic DNS service<br> ↳ <b>WEB-New-File-20-Block</b>: User with no web activity history was blocked from uploading 20MB or more<br><br><b>T1567.002 - Exfiltration Over Web Service: Exfiltration to Cloud Storage</b><br> ↳ <b>WEB-FS</b>: User has accessed a file sharing domain<br> ↳ <b>WEB-OU-FS</b>: One of the top file sharing users in the organization<br> ↳ <b>WEB-OG-FS</b>: One of the top file sharing users in the peer group<br><br><b>T1568.002 - Dynamic Resolution: Domain Generation Algorithms</b><br> ↳ <b>WEB-UD-DynamicDNS</b>: User attempted access to a domain generated using Dynamic DNS service<br><br><b>T1568 - Dynamic Resolution</b><br> ↳ <b>A-WEB-DynamicDNS</b>: Asset attempted access to a domain generated using Dynamic DNS service |  • <b>WEB-OG-FS</b>: File sharing activities of users in the peer group<br> • <b>WEB-OU-FS</b>: File sharing activities of users in the organization    |