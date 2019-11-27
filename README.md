### OpenLMI
---
http://docs.openlmi.org/en/latest/


```py
c = connect("my.server.org", "root", "opensesame")
cups = c.root.cimv2.LMI_Service.first_instance({"Name" : "cups.service"})
cups.StartService()
```

```
```

```
```


