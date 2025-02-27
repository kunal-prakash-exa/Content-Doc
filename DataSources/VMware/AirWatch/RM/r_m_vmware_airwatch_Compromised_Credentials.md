Vendor: VMware
==============
### Product: [AirWatch](../ds_vmware_airwatch.md)
### Use-Case: [Compromised Credentials](../../../../UseCases/uc_compromised_credentials.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  10   |   5    |     2      |      3      |    3    |

| Event Type    | Rules    | Models    |
| ---- | ---- | ---- |
| authentication-successful | <b>T1078 - Valid Accounts</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-GC-new</b>: Abnormal country for group by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>UA-UC-Three</b>: Activity from 3 different countries<br><br><b>T1133 - External Remote Services</b><br> ↳ <b>UA-UI-F</b>: First activity from ISP<br> ↳ <b>UA-UC-new</b>: Abnormal country for user by new user<br> ↳ <b>UA-GC-new</b>: Abnormal country for group by new user<br> ↳ <b>UA-OC-new</b>: Abnormal country for organization by new user<br> ↳ <b>UA-UC-Suspicious</b>: Activity from suspicious country<br> ↳ <b>UA-UC-Two</b>: Activity from two different countries<br> ↳ <b>UA-UC-Three</b>: Activity from 3 different countries |  • <b>UA-OC</b>: Countries for organization<br> • <b>UA-GC</b>: Countries for peer groups<br> • <b>UA-UC</b>: Countries for user activity<br> • <b>UA-UI-new</b>: ISP of users during application activity |
| failed-logon    | <b>T1078 - Valid Accounts</b><br> ↳ <b>SEQ-UH-04</b>: Failed logon by a service account<br> ↳ <b>SEQ-UH-05</b>: Failed interactive logon by a service account<br> ↳ <b>SEQ-UH-07</b>: Failed logon to an asset that user has not previously accessed    |  • <b>AE-UA</b>: All activity for users    |