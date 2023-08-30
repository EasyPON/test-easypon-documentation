---
title: Periodic Tasks
slug: KL4G-periodic-tasks
createdAt: Wed Nov 23 2022 14:48:51 GMT+0000 (Coordinated Universal Time)
updatedAt: Fri Mar 24 2023 19:57:20 GMT+0000 (Coordinated Universal Time)
---

# Periodic Tasks

List of periodic tasks created in the system in the form of a table with fields:

* Name - the title of the periodic task
* OLT Name - the title of the OLT on which the task should be executed
* Last run - last date and time the task was run
* Activity – task activity status. It can be Yes or No.
* View - a link to view detailed information about a specific task.

![Tasks list](../.gitbook/assets/3sLVjT2Vh1H7nk80U50mo\_screencapture-ep-stg-disoft-dev-periodic-task-2022-11-24-002058.png)

## Periodic Task view

Clicking on the View button from the Tasks table displays detailed information about the recurring task.

![Periodic Task page](../.gitbook/assets/YzshMW0B9dgKQFYiSgR4Z\_screencapture-ep-stg-disoft-dev-periodic-task-87-info-2022-11-24-002147.png)

### Quick Actions Bar

* Кнопки Back – return to the list of periodic tasks
* Deactivate – task deactivation.

### Periodic Task information card

* Description - detailed description of the task
* The month of the year - the number of the month of the year when the task should be performed
* Day of month - the day of the month when the task is to be performed
* Day of week - the day of the week when the task is to be performed
* Hour - the hour when the task is to be performed
* Minute - the minute the task is due

## Periodic Task Editing

> Periodic Task can only be edited when it is deactivated

![Periodic Task editing form](../.gitbook/assets/nh47Z8HdMJqJ2SG13ExG1\_screencapture-ep-stg-disoft-dev-periodic-task-130-info-2022-12-04-230834.png)

You can set a value on the editing form:

* Description - detailed description of the task
* The month of the year - the number of the month of the year when the task should be performed
* Day of month - the day of the month when the task is to be performed
* Day of week - the day of the week when the task is to be performed
* Hour - the hour when the task is to be performed
* Minute - the minute the task is due

## Available periodic tasks

The are several tasks available in the EasyPON system for maintaining and automating everyday routines from synchronizing data to performing backups of valuable system data.

### OLT related tasks

* Find unregistered onu - a periodic task for monitoring and updating the list of unregistered ONU
* Update Olt card, ports info - updates OLT and ports data
* Check olt is alive - updates OLT online status
* Save olt config - saves OLT configuration data for every night
* Update measurement Onu - updates registered ONU measurements
* Full sync data of all onu - updates ONU data
* Update client mac address and ethernet porn info on onus

### Switch related tasks

* Update port info in the switch
