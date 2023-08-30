---
title: ONU
slug: DbMW-onu
createdAt: Fri Nov 04 2022 15:46:40 GMT+0000 (Coordinated Universal Time)
updatedAt: Tue Mar 07 2023 23:08:17 GMT+0000 (Coordinated Universal Time)
---

# ONU detailed info

The ONU page displays data on the selected ONU and consists of several sections:

[Quick actions panel](onu.md#quick-actions-panel) - quick commands are available on the quick actions panel that can be executed on the page or from the ONU\
[Information](onu.md#information) - general information about ONU\
[Stats](onu.md#stats) - Display of ONU statistical data\
[ONU Ports](onu.md#onu-ports) - ONU display with available ports and their status\
[ONU location](onu.md#onu-location) - functional of pointing ONU on the map and changing it\
[Ethernet ports](onu.md#ethernet-ports) - display of ONU Ethernet ports\
[Charts](onu.md#charts) - graphs with optical signal readings are displayed\
[Graph Tx/Rx](onu.md#graph-tx-rx) - the graph represents the readings of the optical Tx/Rx signal\
[Graph attenuations](onu.md#graph-attenuations) - the graph represents the readings of the attenuation signals on OLT and ONU\


<details>

<summary>The header additionally displays information about the ONU's MAC/SN. ONU name and description and OLT name with ONU position on OLT in "Shelf/Slot/Port:Number" format.</summary>

* **Shelf** - ONU position

<!---->

* **Slot** - slot number

<!---->

* **Port** - ONU port number

<!---->

* **Number** – ONU number on the OLT port

</details>

![ONU page](../.gitbook/assets/eGU5GENHX30KaO9WlwDXj\_image.png)

## Quick Actions Panel

<details>

<summary>On the quick actions panel, quick commands are available that can be executed on the page or from the ONU:</summary>

* **Back** - switch to the ONU list

<!---->

* **Show configs** - display in the ONU configuration console

<!---->

* **Change preset** - change the ONU configuration

<!---->

* **Custom Action** - change custom ONU configuration

<!---->

* **Event logs** - redirect us to [Event logs](https://ep.stg.disoft.dev/log?base\_content\_type=21\&base\_object\_id=5193\&itemTitle=1%2F2%2F1%3A1\&page=1) page

</details>

<figure><img src="../.gitbook/assets/o1.png" alt=""><figcaption><p>Quick Actions Panel buttons</p></figcaption></figure>

## Information

<details>

<summary>General information about ONU:</summary>

* **ONU name** - ONU name provided during registration

<!---->

* **ID** - ONU identifier

<!---->

* **Firmware version** - firmware version

<!---->

* **MAC/SN** - mac address or serial number of the ONU

<!---->

* **OLT** - the name of the OLT on which ONU is registered

<!---->

* **Configured type** - ONU configuration type

<!---->

* **Real Type** - ONU type

<!---->

* **Date created** - ONU registration date

<!---->

* **Description** - a detailed description of the ONU

<!---->

* **Last synchronize client mac** - a table of client MAC addresses assigned to the ONU

</details>

<figure><img src="../.gitbook/assets/o2.png" alt=""><figcaption></figcaption></figure>

## Stats

Displaying ONU statistical data in sections:

* **Status** - ONU status
* **Uptime** - a time stamp that shows how many ONUs are online
* **Date modified** - a time marker that shows how much time has passed since the last modification of the ONU
* **Rx/Tx** indicators on OLT, ONU, and signal attenuation (Attenuation)

<figure><img src="../.gitbook/assets/o3.png" alt=""><figcaption></figcaption></figure>

Also there are 3 buttons to interact with ONU:

* **Reboot** - reboot selected ONU
* **Synchronize** - after successful synchronization, all ONU data should be up to date
* **Delete** - delete the ONU from system

## ONU Ports

ONU display with available ports and their status. The connected port type and its operational status.

* **Port type** - port type (Auto, 10m/half(full), 100m/half(full), 1000m/full)
* **Port status** - administrative port status (Auto, Down)

<figure><img src="../.gitbook/assets/o4.png" alt=""><figcaption></figcaption></figure>

## ONU location

Shows ONU location on the map. If we move the mouse cursor over the label of ONU displays additional information, such as: ONU's amount, address, status and commentary.&#x20;

<figure><img src="../.gitbook/assets/o5 (1).png" alt=""><figcaption></figcaption></figure>

Also If the map extended there are 2 buttons:&#x20;

* **Create building** - creating new ONU location&#x20;
*   **Edit location** - edit an existing ONU  location



<div>

<figure><img src="../.gitbook/assets/create.png" alt="" width="304"><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/ed.png" alt="" width="563"><figcaption></figcaption></figure>

</div>

##

## Ethernet Ports

<details>

<summary>Ethernet Ports consist of table with futher fields:</summary>

* **Admin status** - the administrative status of the Ethernet port (can be Auto or Down)

<!---->

* **Oper. status** - operational status

<!---->

* **Vlans** - available Vlans ports

<!---->

* **Type** - port type

<!---->

* **Speed** - port speed

</details>

<figure><img src="../.gitbook/assets/o6.png" alt=""><figcaption></figcaption></figure>

## Charts

This section displays graphs with readings of the optical signal, collected by periodic polling once every set number of minutes (hours). Attenuations and Tx/Rx signals are displayed in separate graphs.

## Graph Tx/Rx

The graph represents the readings of the optical Tx/Rx signal. It is possible to view data statistics for the last 24 hours, yesterday, 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Graph Tx/Rx](../.gitbook/assets/zDdW\_wuvW2Pwz25QvTsjK\_image.png)

## Graph attenuations

The graph represents the readings of the attenuation signals on OLT and ONU. It is possible to view data statistics for the last 24 hours, yesterday, 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Graph attenuations](../.gitbook/assets/ypjzai\_byXXxqvKCgqh\_X\_image.png)
