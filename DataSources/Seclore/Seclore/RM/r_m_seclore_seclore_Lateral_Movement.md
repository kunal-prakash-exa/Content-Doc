Vendor: Seclore
===============
### Product: [Seclore](../ds_seclore_seclore.md)
### Use-Case: [Lateral Movement](../../../../UseCases/uc_lateral_movement.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|  14   |   7    |     1      |      3      |    3    |

| Event Type   | Rules    | Models    |
| ---- | ---- | ---- |
| share-access | <b>T1021.002 - Remote Services: SMB/Windows Admin Shares</b><br> ↳ <b>A-SA-OU-F</b>: First admin share access to asset for this user in the organization<br> ↳ <b>A-SA-OU-A</b>: Abnormal admin share access to asset for the user in the organization<br> ↳ <b>A-SA-OH-F</b>: First admin share on asset for organization<br> ↳ <b>A-SA-OH-A</b>: Abnormal admin share on asset in organization<br> ↳ <b>A-SA-ZH-F</b>: First admin share on asset in the zone<br> ↳ <b>A-SA-ZH-A</b>: Abnormal admin share on asset for zone<br> ↳ <b>A-SA-AsU-F</b>: First access of admin share on asset<br> ↳ <b>A-SA-AsU-A</b>: Abnormal access of admin share on the asset<br> ↳ <b>SA-OU-F</b>: First admin share access for user in the organization<br> ↳ <b>SA-OU-A</b>: Abnormal admin share access for user in the organization<br> ↳ <b>SA-OH-F</b>: First admin share on this host<br> ↳ <b>SA-OH-A</b>: Abnormal admin share on this host<br> ↳ <b>SA-AsU-F</b>: First access of admin share on this host<br> ↳ <b>SA-AsU-A</b>: Abnormal access of admin share on this host |  • <b>SA-AsU</b>: Users accessing this Admin share<br> • <b>SA-OH</b>: Assets on which admin share is accessed in organization<br> • <b>SA-OU</b>: Users accessing admin share in the organization<br> • <b>A-SA-AsU</b>: Users per Admin share<br> • <b>A-SA-ZH</b>: Dest zones on which admin shares are accessed<br> • <b>A-SA-OH</b>: Assets on which admin shares are accessed in organization<br> • <b>A-SA-OU</b>: Admin Share users in organization |