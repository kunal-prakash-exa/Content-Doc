Vendor: Citrix
==============
### Product: [Web Logging](../ds_citrix_web_logging.md)
### Use-Case: [Abnormal Authentication & Access](../../../../UseCases/uc_abnormal_authentication_&_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   7   |   7    |     2      |      2      |    2    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| failed-physical-access | <b>T1078 - Valid Accounts</b><br> ↳ <b>PA-VPN-02</b>: Badge access after VPN login    |  • <b>PA-VPN-02</b>: Users who accessed a physical location after vpn login    |
| web-activity-allowed   | <b>T1071.001 - Application Layer Protocol: Web Protocols</b><br> ↳ <b>WEB-UUa-OS-F</b>: First web activity using this operating system for this user<br> ↳ <b>WEB-UUa-MobileBrowser-F</b>: First activity using this mobile web browser/app for this user to a new domain<br> ↳ <b>WEB-OsUa-MobileBrowser-F</b>: First activity using this mobile web browser for this mobile operating system<br> ↳ <b>WEB-UT-TOW-A</b>: Abnormal day for this user to access the web via the organization<br> ↳ <b>WEB-UZ-F</b>: First web activity for this user in this zone<br> ↳ <b>WEB-GZ-F</b>: First web activity from this zone for the peer group |  • <b>WEB-GZ</b>: Network zones where users performs web activity in the peer group<br> • <b>WEB-UZ</b>: Network zones where a user performs web activity from<br> • <b>WEB-UT-TOW</b>: Web activity activity time for user<br> • <b>WEB-OsUa-MobileBrowser-New</b>: Top mobile apps/web browsers being used in the organization for this type of device<br> • <b>WEB-UUa-MobileBrowser-New</b>: Top mobile apps/web browsers being used by user<br> • <b>WEB-UUa-OS-New</b>: Top operating systems being used to connect to the web for user |