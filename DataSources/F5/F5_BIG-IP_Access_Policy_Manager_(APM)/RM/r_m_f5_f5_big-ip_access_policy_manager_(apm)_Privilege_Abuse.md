Vendor: F5
==========
### Product: [F5 BIG-IP Access Policy Manager (APM)](../ds_f5_f5_big-ip_access_policy_manager_(apm).md)
### Use-Case: [Privilege Abuse](../../../../UseCases/uc_privilege_abuse.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   9   |   3    |     3      |      6      |    6    |

| Event Type   | Rules    | Models    |
| ---- | ---- | ---- |
| app-activity | <b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Ex</b>: A user has been given mailbox permissions for an executive user<br> ↳ <b>EM-InB-Perm-N-F</b>: First time a user has given mailbox permissions on another mailbox that is not their own<br> ↳ <b>EM-InB-Perm-N-A</b>: Abnormal for user to give mailbox permissions<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account<br> ↳ <b>APP-F-SA-NC</b>: New service account access to application<br> ↳ <b>APP-AT-PRIV</b>: Non-privileged user performing privileged application activity |  • <b>EM-InB-Perm-N</b>: Models users who give mailbox permissions<br> • <b>APP-AT-PRIV</b>: Privileged application activities    |
| vpn-login    | <b>T1078 - Valid Accounts</b><br> ↳ <b>SL-UA-F-VPN</b>: First VPN connection for service account<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>SL-UA-F-VPN</b>: First VPN connection for service account    |    |
| vpn-logout   | <b>T1098.002 - Account Manipulation: Exchange Email Delegate Permissions</b><br> ↳ <b>EM-InB-Perm-A</b>: Abnormal number of mailbox permission given by user.<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>WPA-UACount</b>: Abnormal number of privilege access events for user    |  • <b>EM-InB-Perm</b>: Models the number of mailbox permissions given by this user.<br> • <b>WPA-UACount</b>: Count of admin privilege events for user |