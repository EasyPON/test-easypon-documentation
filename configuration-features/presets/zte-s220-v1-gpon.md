---
description: Preset for ONU you want to register on this OLT
---

# ZTE с220 v1 GPON

```
// ZTE с220 v1 GPON Preset
interface  {{onu.port_interface}} 
onu {{onu_number}} type {{onu_type.value}} mac {{onu.mac_address | split:"."}} ip-cfg static
!
interface  {{onu.onu_interface}} 
property description {{input_params.name}}
switchport mode trank vport 1
switchport vlan {{input_params.vlan}}  tag vport 1
port-location sub-option remote-id enable vport 1
dhcp-option82 disable vport 1
!
pon-onu-mng  {{onu.onu_interface}} 
vlan port eth_0/1 mode tag vlan  {{input_params.vlan}}
dhcp-ip ethuni eth_0/1 from-internet
```
