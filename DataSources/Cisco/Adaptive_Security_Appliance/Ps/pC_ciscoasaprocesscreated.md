#### Parser Content
```Java
{
Name = cisco-asa-process-created
  Vendor = Cisco
  Product = Adaptive Security Appliance
  Lms = Direct
  DataType = "process-created"
  IsHVF = true
  TimeFormat = "MMM dd yyyy HH:mm:ss"
  Conditions = [ "-111008", "%ASA-" ]
  Fields = [
    """exabeam_time=({time}\d\d\d\d-\d\d-\d\d \d\d:\d\d:\d\d)""",
    """exabeam_host=(::ffff:)?(.+?@\s{0,100})?({host}[\w.\-]{1,2000})""",
    """({time}\w+ \d{1,100} \d{4} \d\d:\d\d:\d\d)""",
    """%ASA\-({priority}\d{1,100})\-({event_code}\d{1,100})""",
    """User\s{1,100}'({user}[^']{1,2000})'""",
    """({event_name}executed)\s{1,100}the\s{1,100}'({command_line}[^']{1,2000})\s{0,100}'"""
  ]


}
```