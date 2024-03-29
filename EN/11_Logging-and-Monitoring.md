# Logging and Monitoring

([Back](../README.md))

## Objective

Enable logging for the cloud environment and for cloud-based workloads.

## Applicable Service Models

- IaaS, PaaS, SaaS

| Mandatory Requirements                                                                                                                                   | Validation                                                                                                                                                                                                                                                                                                                                                                                                         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <ul><li>Implement adequate level of logging and reporting, including a security audit log function in all information systems.</li></ul>                 | <ul><li>Confirm policy for event logging is implemented.</li><li>This includes logs for the following: <ol><li>Sign-in logs (interactive and non-interactive sign-ins, API sign-ins)</li><li>Access privilege and group changes (including group membership and group privilege assignment)</li><li>Changes in configuration of cloud platform</li><li>Cloud resource provisioning activities.</li></ol></li></ul> |
| <ul><li>Configure events within the solution to support security monitoring, in accordance with GC Event Logging Guidance.</li></ul>                     | <ul><li>Confirm if monitoring and auditing is implemented for all users.</li></ul>                                                                                                                                                                                                                                                                                                                                 |
| <ul><li>Ensure that the appropriate contact information is configured so that the CSP can notify the GC organization of incidents they detect.</li></ul> | <ul><li>Confirm that the security contact record within the account should be completed with details of at least two (if multiple permitted by cloud platform) appropriate information security personnel.</li></ul>                                                                                                                                                                                               |
| <ul><li>Configure an appropriate time zone for the audit records generated by your solution components.</li></ul>                                        | <ul><li>Confirm that the appropriate time zone has been set.</li></ul>                                                                                                                                                                                                                                                                                                                                             |
| <ul><li>Ensure that resources are assigned to monitor cloud-based events</li></ul>                                                                       | <ul><li>Demonstrate that the monitoring use cases for the cloud platform have been implemented and have been integrated with the overall security monitoring activities being performed by the department. Evidence could include monitoring run book/checklist, system generated report.</li></ul>                                                                                                                |

| Additional Considerations |
| ------------------------- |
| None                      |

## References

1. [SPIN 2017-01](https://www.canada.ca/en/treasury-board-secretariat/services/access-information-privacy/security-identity-management/direction-secure-use-commercial-cloud-services-spin.html), subsection 6.3.1
2. CSE Top 10 #1, 5, 8
3. Refer to [GC Event Logging Guidance](https://www.gcpedia.gc.ca/gcwiki/images/e/e3/GC_Event_Logging_Strategy.pdf)
4. Refer to [ITSP.50.104 Guidance on defence in depth for cloud-based services](https://cyber.gc.ca/en/guidance/itsp50104-guidance-defence-depth-cloud-based-services), subsection 4.8

Related security controls: AU‑12, SI-4, SI-4(7)
