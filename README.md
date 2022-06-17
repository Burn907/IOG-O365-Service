# O365-Service-Engineering

Service support information for providing O365 services for RSG

O365 is a SAAS solution providing collaboration services such as Outlook, Teams, SharePoint and the Power Platform for all RSG eomployees. The O365 tenant is shared across RELX and is accessable using corporate identities in the current Hybrid AD > AzureAd architecture.

The RELX O365 tenant is shared across all RELX Business Units as a single shared environment.
For legal purposes, the tenant is hosted in the East US region within Microsofts cloud infrastructure for O365 services. All identities and data within the tenant must remain within the North US region.

**Service Health**

Monitor O365 Service Health from the service health blade in the Admin center
https://admin.microsoft.com/#/servicehealth

Service degredation and advisories are listed here for each individual service within O365. Service degredations are also emailed to admins once Microsoft aknowledge an issue

In addition to the O365 services, you can also monitor Windows release health in a seperate blade
https://admin.microsoft.com/#/windowsreleasehealth

**Service Support**

All issues related to O365 must be report to the RSG Level I ServiceDesk/Helpdesk.

**Level I** = 10 minute first time fix
Issue is logged into Topdesk and the analyst will collect details of the issue from the caller and attempt to resolve if it is a local issue.
If the issue is not resolved within 10 minutes, the ticket is escalated to local Level II support

**Level II** = Will pickup ticket from Topdesk and contact the caller. All attempts will be made to resolve if the problem is an isolated client side issue.
If the issue cannot be resolved or it is impacting a wider audiance, the ticket will be escalated to Level III O365 Administration

**Level III** = O365 Admininistration will pickup the ticket and looks to resolve accordingly. Incidents that are impacting RSG on a wide scale will either be environment related or Microsoft service degredation.

**Environment**
The issue could be related to connectivity in our hybrid architecture. The correct licenses must be assigned to the identity in order to access O365 services and activation.

Microsoft admins can view the status of services and find out when maintenance is scheduled. Service health information is available at any time by signing in. 

View status of services: The Service health section shows the current status of the service and details about service disruptions and outages. Planned maintenance information is available on the Message Center. For more information, see View the status of your services.

Service incidents: A service incident is an event that affects the delivery of a service. Service incidents may be caused by hardware or software failure in the Microsoft data center, a faulty network connection due to a change made by Microsoft, or a major data center challenge such as fire, flood, or regional catastrophe. Interruptions caused by third party service providers, or changes made within customer managed environment, aren't considered service incidents. Most service incidents can be addressed using Microsoft technology and process solutions and are resolved within a short time. However, some service incidents are more serious and can lead to longer term outages.

Service notifications: There are two types of notifications about times when services may not be available: Planned maintenance events and Unplanned downtime.

Planned maintenance events: Planned maintenance is regular Microsoft-initiated service updates to the infrastructure and software applications. Planned maintenance notifications inform customers about service work that might affect the functionality of a Microsoft service. Customers are notified no later than five days in advance of all planned maintenance through Message center on the Microsoft 365 admin center. Microsoft typically plans maintenance for times when service usage is historically at its lowest based on regional time zones.

Unplanned downtime: Unplanned service incidents occur when one of the services is unavailable or unresponsive due to a failure within the Microsoft managed environment. Customers are notified of known service incidents through Service health on the Microsoft 365 admin center.

Recent worldwide uptimes: Moving to a cloud service shouldn't mean losing the ability to know what's going on. With Microsoft 365, it doesn't. We aim to be transparent in our operations so you can monitor the state of your service, track issues, and have a historical view of availability. The following tables show recent worldwide uptime data.

Years	Q1	Q2	Q3	Q4
2022			
2021	99.97%	99.98%	99.99%	99.98%
2020	99.98%	99.99%	99.97%	99.97%
2019	99.97%	99.97%	99.98%	99.98%
2018	99.99%	99.98%	99.97%	99.98%
2017	99.99%	99.97%	99.98%	99.99%

Notification policy: When a service incident occurs, Microsoft recognizes that timely, targeted, and accurate communications are critical for customers. Microsoft notifies administrators by communicating directly to impacted customers via Service health on the Microsoft 365 admin center. Service incident updates are provided on an hourly cadence or, if a different cadence is required, it will be stated in the SHD communication posting.

Ensuring data availability: Microsoft ensures that customer data is available whenever it's needed through the following features: Data storage and redundancy, Data monitoring, and Completing preventative maintenance.

Data storage and redundancy: Customer data is stored in a redundant environment with robust data protection capabilities to enable availability, business continuity, and rapid recovery. Multiple levels of data redundancy are implemented, ranging from redundant disks to guard against local disk failure to continuous, full data replication to a geographically diverse data center.

Data monitoring: Microsoft services maintain high levels of performance by monitoring: Databases, Blocked processes, Packet loss, Queued processes, and Query latency.

Technical support case handling: Microsoft assigns a severity level to a case when it is opened, based on an assessment of the issue type and customer impact. Examples of issue types and severity levels are shown in the following table.

Severity level	Operations and support description	Examples
Sev A (Critical)
One or more services aren't accessible or are unusable. Production, operations, or deployment deadlines are severely affected, or there will be a severe impact on production or profitability. Multiple users or services are affected.
Widespread problems sending or receiving mail.
SharePoint site down.
All users can't send instant messages, join or schedule Skype for Business Meetings, or make Skype for Business calls.
Sev B (High)
The service is usable but in an impaired fashion. The situation has moderate business impact and can be dealt with during business hours. A single user, customer, or service is partially affected.
Send button in Outlook is garbled.
Setting is impossible from EAC (Exchange Admin Center) but possible in PowerShell.
Sev C (Non-critical)
The situation has minimal business impact. The issue is important but doesn't have a significant current service or productivity impact for the customer. A single user is experiencing partial disruption, but an acceptable workaround exists.
How to set user password that never expires.
User can't delete contact information in Exchange Online.
Technical support initial response times: Initial response time is based on the severity levels described above and the type of subscription. The response time objectives are described in the following table.


Sev A (Critical)
Available: 24/74
Response time: one hour
Available: 24/74
Response time: one hour
Available: 24/74
Response time: one hour

Sev B (High)
Available: business hours
Response time: no commitment
Available: 24/74
Response time: next day
Available: 24/74
Response time: 2 hours

Sev C (Medium)
Available: business hours
Response time: no commitment
Available: 24/74
Response time: no commitment
Available: 24/74
Response time: 4 hours


**Service	Location**

|                                                            |               |
| ---------------------------------------------------------- | ------------- |
| Exchange Online                                            | United States |
| OneDrive for Business                                      | United States |
| SharePoint Online                                          | United States |
| Microsoft Teams                                            | United States |
| Office Online & Mobile                                     | United States |
| EOP                                                        | United States |
| Intune                                                     | United States |
| Planner                                                    | United States |
| Sway                                                       | United States |
| Yammer                                                     | United States |
| OneNote Services                                           | United States |
| Stream                                                     | United States |
| Whiteboard                                                 | United States |
| Forms                                                      | United States |
| Viva Connections                                           | United States |
| Viva Topics                                                | United States |
| Viva Learning                                              | United States |
| Viva Insights - Personal                                   | United States |
| Viva Insights - Manager/Leader AAD org data only           | United States |
| Viva Insights - Manager/Leader with 3rd party HR data only | United States |
| Viva Insights - Advanced                                   | United States |

**How does Microsoft secure your data?**

Microsoft has robust policies, controls, and systems built into Microsoft 365 to help keep your information safe. Review the Microsoft 365 security section on the Microsoft Trust Center to learn more.

**Does Microsoft 365 encrypt your data?**

Microsoft 365 uses service-side technologies that encrypt customer data at rest and in transit. For customer data at rest, Microsoft 365 uses volume-level and file-level encryption. For customer data in transit, Microsoft 365 uses multiple encryption technologies for communications between data centers and between clients and servers, such as Transport Layer Security (TLS) and Internet Protocol Security (IPsec). Microsoft 365 also includes customer-managed encryption features.
