Vendor: Hornet
==============
### Product: [Hornet Email](../ds_hornet_hornet_email.md)
### Use-Case: [Privilege Abuse](../../../../UseCases/uc_privilege_abuse.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   5    |     1      |      5      |    5    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| dlp-email-alert-in         | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| dlp-email-alert-in-failed  | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| dlp-email-alert-out        | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| dlp-email-alert-out-failed | <b>T1078 - Valid Accounts</b><br> ↳ <b>APP-Account-deactivated</b>: Activity from a de-activated user account    |    |
| privileged-access          | <b>T1078 - Valid Accounts</b><br> ↳ <b>WPA-OU-F</b>: First privileged access event for user for organization<br> ↳ <b>WPA-OG-F</b>: First privileged access event for user for peer group<br> ↳ <b>WPA-UH-F</b>: First privileged access event on host for user<br> ↳ <b>WPA-HZ-F</b>: First privileged access event on host from zone<br> ↳ <b>WPA-USH-F</b>: First privileged access event on source host for user |  • <b>WPA-USH</b>: Source hosts with privileged access events for user<br> • <b>WPA-HZ</b>: Source zones with privileged access events for host<br> • <b>WPA-UH</b>: Hosts with privileged access events for user<br> • <b>WPA-OG</b>: Privileged access activity for users in the peer group<br> • <b>WPA-OU</b>: Privileged access activity for users in the organization |