Vendor: Fidelis
===============
### Product: [Fidelis Network](../ds_fidelis_fidelis_network.md)
### Use-Case: [Abnormal Authentication & Access](../../../../UseCases/uc_abnormal_authentication_&_access.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   6   |   3    |     2      |      2      |    2    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| failed-logon    | <b>T1110 - Brute Force</b><br> ↳ <b>SEQ-UH-09</b>: Abnormal time of the week for a failed logon for user<br> ↳ <b>SEQ-UH-10</b>: Failed logons had multiple reasons<br><br><b>T1078 - Valid Accounts</b><br> ↳ <b>SEQ-UH-03</b>: Failed logon to a top failed logon asset by user<br> ↳ <b>SEQ-UH-06</b>: Abnormal failed logon to asset by user<br> ↳ <b>SEQ-UH-07</b>: Failed logon to an asset that user has not previously accessed |  • <b>FL-UH</b>: All Failed Logons per user<br> • <b>FL-OH</b>: All Failed Logons in the organization |
| failed-physical-access | <b>T1078 - Valid Accounts</b><br> ↳ <b>PA-VPN-02</b>: Badge access after VPN login    |  • <b>PA-VPN-02</b>: Users who accessed a physical location after vpn login    |