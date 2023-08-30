# Switch

The list of connected switches in the EasyPON system is presented in the form of a Switch List table. You can connect it easily by filling the required fields:

<figure><img src=".gitbook/assets/Screenshot 2023-05-04 at 15.53.18 (1).png" alt=""><figcaption></figcaption></figure>

View information about a specific Switch, make actions, view Logs and look up to the Clients MAC addresses.

![Specific Switch page](<.gitbook/assets/Screenshot 2023-05-04 at 15.58.52.png>)

You can change the Admin Status on the switch port. Also, each port displays the client MAC addresses on which the [global search](onu-workspace/onu-search.md) works.

## Ports

<details>

<summary>The block displays the list of ports on the switch in tabular form. The following information is available in the table:</summary>

Port - Switch port number

Name - Switch name

Admin Status - the administrative status of the Switch port

Oper Status -the operational status of the Switch port

Vlans - number and type of Vlans

Type - port type Switch

Errors - number of Uplink and Downlink data errors

Traffic - the amount of Uplink and Downlink traffic data

Client mac addresses - client mac addresses on the Switch port

</details>

<figure><img src=".gitbook/assets/Screenshot 2023-05-04 at 16.03.41.png" alt=""><figcaption></figcaption></figure>

## Event logs

For your convenience we added Event log button to the Switch detailed info page. It will navigate you to the filtered [Event log page](switch.md#event-logs) by Switch, you would like to see changes with.

## Synchronize

By clicking the Synchronize button located in the Quick Actions Bar section on the Switch page, it is feasible to synchronize the connection and data with the existing Switch. Once the synchronization process is successful, all data related to the Switch should be current and up-to-date.

### Admin Status change

By clicking on the port Admin Status icon in the table, you can change the administrative status on the Switch port. Also, each port displays the client MAC addresses on which the [global search](onu-workspace/onu-search.md) works.

<figure><img src=".gitbook/assets/Screenshot 2023-05-04 at 16.04.03.png" alt="" width="375"><figcaption><p>Dialogue window of admin status change action</p></figcaption></figure>

## Delete Switch

The Switch can be deleted by pressing the Delete button in the Quick Actions Bar section on the Switch page. To delete Switch from the EasyPON system user confirmation is required.
