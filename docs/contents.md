| [Home](../README.md) |
| -------------------- |

# Contents

The **USB Management Exceptions** solution pack contains the following resources.

## Dashboards 

| Name                                      | Description                                                                                                                                                                            |
|:------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| USB Approval System                       | Displays USB Request Status and USB Request Status (Validation)                                                                                                                        |
## Connectors

| Name                                    | Description                                                                                                                                         |
|:----------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|
| Fortinet FortiEDR                       | FortiEDR Connector to Move Collectors from Current Group to allow USB Group.                                                                         |
| Microsoft Exchange                      | Microsoft Exchange connector fetches Request and approval by Email.                                                                                 |
| Microsoft Active Directory              | Microsoft Active Directory Connector to get requester information and Manager details.                                                              |



## Module Schema

| Name         | Description                                                                                  |
|:-------------|:---------------------------------------------------------------------------------------------|
| USBs         | A module contains Requester Name,Requester Username, Requester Email, Manager Name, Manager Email, Machine Name , Request Status , Manager Justification, Manager Approval Status, Allowed Until and  Validation Status|


## Picklists

| Name                                   |
|:---------------------------------------|
| USBUSerRequest                         |
| Validation                             |
| Request Status                         |


## Schedules

| Name                                                                 | Description                                                                                   |
|:---------------------------------------------------------------------|:----------------------------------------------------------------------------------------------|
| Remove USB Permission                                                | This schedule is triggered every 5 minutes to revoke USB Access                               |


## Playbook Collection

| 02 - Use Case - USB Approval System   |
| :------------------------------------ |

| Playbook Name                                              | Description                                                                                 |
|:-----------------------------------------------------------|:--------------------------------------------------------------------------------------------|
| Collector Movement Validation                                             | This playbook verifies collector movements and notifies relevant parties of errors.                                  |
| USB Access Request                                    |     This playbook automates USB access request approvals.      |
| USB Permission Revocation                                        | This playbook automates revoking USB access permissions when they expire.                                      |


>**WARNING:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.

# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|
