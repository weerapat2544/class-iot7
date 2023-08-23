![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301014/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301014",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301014/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301014",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301014/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301014",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "geo-location",
    "value"     : "125,250"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/get/6310301014/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301014",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "status",
    "value"     : "main"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/Monitor/6310301014/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301014",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "main"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/get/6310301014/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301014",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "main"
}
```
