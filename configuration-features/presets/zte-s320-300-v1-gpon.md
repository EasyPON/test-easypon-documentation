---
description: Preset for ONU you want to register on this OLT
---

# ZTE с320/300 v1 GPON

To start, you need to describe OLT profiles:

```
gpon     
  profile tcont UP-1000Mb type 4 maximum 1024000
  profile traffic DOWN-1000Mb sir 1024000 pir 1024000
!
onu-profile gpon line 1000mb
  fec upstream
  tcont 1 name T-INET profile UP-1000Mb
  gemport 1 name G-INET tcont 1
  gemport 1 traffic-limit downstream DOWN-1000Mb 
!
pon
onu-profile gpon remote standart
  gemport 1 flow 1
!
```

Then add this preset to the [Preset list](../presets.md) in EasyPON and start to use it while registering ONU.

```
interface  {{onu.port_interface}} 
onu  {{onu_number}}  type {{onu_type.value}}  sn  {{onu.serial_number}} 
onu {{onu_number}} profile  line 1000mb remote standart
!
interface  {{onu.onu_interface}} 
name {{input_params.name}}
switchport mode trank vport 1
switchport vlan {{input_params.vlan}}  tag vport 1
port-location sub-option remote-id enable vport 1
dhcp-option82 enable vport 1
dhcp-option82 trust true keep vport 1
!
pon-onu-mng  {{onu.onu_interface}} 
vlan port eth_0/1 mode tag vlan  {{input_params.vlan}}
dhcp-ip ethuni eth_0/1 from-internet
```
