---
title: "J.XUAN WSZ01 control via MQTT"
description: "Integrate your J.XUAN WSZ01 via Zigbee2MQTT with whatever smart home infrastructure you are using without the vendor's bridge or gateway."
addedAt: 2021-05-30T19:17:03Z
pageClass: device-page
---

<!-- !!!! -->
<!-- ATTENTION: This file is auto-generated through docgen! -->
<!-- You can only edit the "Notes"-Section between the two comment lines "Notes BEGIN" and "Notes END". -->
<!-- Do not use h1 or h2 heading within "## Notes"-Section. -->
<!-- !!!! -->

# J.XUAN WSZ01

|     |     |
|-----|-----|
| Model | WSZ01  |
| Vendor  | [J.XUAN](/supported-devices/#v=J.XUAN)  |
| Description | Wireless switch |
| Exposes | action, battery |
| Picture | ![J.XUAN WSZ01](https://www.zigbee2mqtt.io/images/devices/WSZ01.png) |


<!-- Notes BEGIN: You can edit here. Add "## Notes" headline if not already present. -->


<!-- Notes END: Do not edit below this line -->




## Exposes

### Action (enum)
Triggered action (e.g. a button click).
Value can be found in the published state on the `action` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The possible values are: `release`, `single`, `double`, `hold`.

### Battery (numeric)
Remaining battery in %, can take up to 24 hours before reported.
Value can be found in the published state on the `battery` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `100`.
The unit of this value is `%`.

