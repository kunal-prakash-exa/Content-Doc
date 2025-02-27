Vendor: AssetView
=================
### Product: [AssetView](../ds_assetview_assetview.md)
### Use-Case: [Data Leak](../../../../UseCases/uc_data_leak.md)

| Rules | Models | MITRE TTPs | Event Types | Parsers |
|:-----:|:------:|:----------:|:-----------:|:-------:|
|   5   |   2    |     2      |      5      |    5    |

| Event Type     | Rules    | Models    |
| ---- | ---- | ---- |
| file-write     | <b>T1114.001 - T1114.001</b><br> ↳ <b>FA-Outlook-pst</b>: A file ends with either  pst or ost    |    |
| print-activity | <b>T1052 - Exfiltration Over Physical Medium</b><br> ↳ <b>PR-UP-F</b>: First print activity from printer for user<br> ↳ <b>PR-UP-A</b>: Abnormal printer for user<br> ↳ <b>PR-UT-TOW</b>: Abnormal print activity time for user<br> ↳ <b>PR-SRC-CODE</b>: Printed document with source code file extension |  • <b>PR-UT-TOW</b>: Print activity time for user<br> • <b>PR-UP</b>: Printers for user |