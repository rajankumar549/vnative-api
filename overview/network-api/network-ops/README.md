# Network Operations

_**Some Network Operations**_

## **Available methods**

| Operation | HTTP Method | End Point | Description |
| :--- | :--- | :--- | :--- |
| Acount Info |  |  |  |
|  | GET | [/network/account](account.md) | Get Network Details |
| Edit Account Info |  |  |  |
|  | PATCH | [/network/account](account.md) | Edit Network Details |
| Get Tracking Link |  |  |  |
|  | GET | [/network/link/{affiliateId}/{campaignId}](tracking-link-1.md) | Get the tracking link for an affiliate |
| Create Tracking Link |  |  |  |
|  | POST | [/network/link/{affiliateId}/{campaignId}](tracking-link-1.md) | Create a tracking link for an affiliate for a campaign |
| Network Stats |  |  |  |
|  | GET | [/network/stats](stats.md) | Get Stats for a Network |
|  | GET | [/network/customReport](custom-report.md) | Get Custom Report for a network |
| Network Stats |  |  |  |
|  | GET | [/network/conversions](conversions.md) | Get Conversion Logs |
| Conversion Import |  |  |  |
|  | POST | [/network/conversion-import](conversion-import.md) | Importing Conversions in Trackier |
| Jobs API |  |  |  |
|  | GET | [/jobs](jobs.md) | Get All Jobs |
|  | GET | [/jobs/{id}](jobs.md) | Get Info about a single job |
| [Referral Operations](referral/) |  |  |  |
|  | GET | [/network/referral](referral/read.md) | Get all the Referral Links |
|  | POST | [/network/referral](referral/create.md) | Create a new referral link |
|  | PATCH | [/network/referral/{id}](referral/edit.md) | Edit a referral link |
|  | DELETE | [/network/referral/{id}](referral/delete.md) | Remove a referral link |

