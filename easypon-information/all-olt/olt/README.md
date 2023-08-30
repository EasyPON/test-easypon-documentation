# OLT detailed information

### Quick Actions Panel

**Back** – back to the [OLT list](../)

**Edit** - [OLT editing](../add-olt.md#edit-olt)

**Synchronize** – OLT main data synchronization. After successful synchronization, all OLT data should be up to date.

**Get ONU** – synchronize all ONUs on the current OLT. With the help of Get ONU, it is possible to perform the synchronization process of all ONUs on the OLT Slots & Ports section. This option is available both from the Quick Actions Bar on the OLT page, in separate slots, and on individual OLT ports with an 'Up' Link Status.

<figure><img src="../../.gitbook/assets/Get ONU.webp" alt=""><figcaption></figcaption></figure>

**Delete** - delete the OLT from EasyPON system. OLT can be deleted by pressing the Delete button in the Quick Actions Bar section on the OLT page. To delete the OLT from the EasyPON system user confirmation is required.

![OLT page](<../../.gitbook/assets/Screenshot 2023-04-26 at 15.14.46.png>)

## Slots & Ports

In this block you access the information about slots and ports you have on your OLT.

Ports are displayed in the summary table under the corresponding slot. Selecting a slot in the "Slots" section will display its ports in this section.

<details>

<summary>Port section fields:</summary>

№ - serial number of the port&#x20;

Registered ONU – the number of registered ONUs on the port&#x20;

Admin Status (On/Off) - administrative status of the port&#x20;

Link status (Up/Down) – port connection status&#x20;

QinQ status - the list of QinQ ports&#x20;

Port load - the load on the port in the following format: registered ONUs / total port capacity - port load in percents.&#x20;

Get ONU button – synchronization of all ONUs on the OLT slot

</details>

## Tasks

This block contains the list of active periodic tasks which are running on this OLT. You can read more about periodic tasks [here](../../access-and-management/periodic-tasks.md).

## Graph all ONU / Online ONU

The graph displays the number of all ONUs on the OLT relative to the ONUs that had Online status on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Graph all ONU / Online ONU](../../.gitbook/assets/JF2kp0HIq3RrcF0bmQKoI\_image.png)

## Amount of errors by OLT in the time graph

The graph displays the number of errors on the OLT within a time scale. It is possible to view statistics for the last 24 hours, for yesterday, for 7, 30, and 90 days ago.

Press the indicator in the legend to isolate its view on the graph or press back to select and view all data again. You can also press the Command key on Mac or Windows key on PC for multiple indicators selection and viewing them on the graph.

![Amount of errors by OLT in time graph](../../.gitbook/assets/7oE5NXNEdAUS-J0VDtLmt\_image.png)
