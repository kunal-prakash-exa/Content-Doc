Vendor: Netwrix
===============
### Product: [Netwrix Auditor](../ds_netwrix_netwrix_auditor.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   2    |     4      |     15      |   15    |

| Event Type     | Rules    | Models    |
| ---- | ---- | ---- |
| app-activity   | <b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>Auth-Tor-Shost</b>: User authentication or login from a known TOR IP    |    |
| app-login      | <b>T1090.003 - Proxy: Multi-hop Proxy</b><br> ↳ <b>Auth-Tor-Shost</b>: User authentication or login from a known TOR IP    |    |
| nac-logon      | <b>T1078 - Valid Accounts</b><br> ↳ <b>NAC-UL-F</b>: First network location for user<br> ↳ <b>NAC-UL-A</b>: Abnormal network location for user<br> ↳ <b>NAC-UM-F</b>: First MAC for user<br> ↳ <b>NAC-UM-A</b>: Abnormal MAC for user<br><br><b>T1021 - Remote Services</b><br> ↳ <b>NAC-UL-F</b>: First network location for user<br> ↳ <b>NAC-UL-A</b>: Abnormal network location for user |  • <b>NAC-UM</b>: MAC addresses for user<br> • <b>NAC-UL</b>: Network locations for user |
| security-alert | <b>T1027.005 - Obfuscated Files or Information: Indicator Removal from Tools</b><br> ↳ <b>A-ALERT-DL</b>: DL Correlation rule alert on asset<br> ↳ <b>ALERT-DL</b>: DL Correlation rule alert on asset accessed by this user    |    |