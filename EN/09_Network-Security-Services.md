# Network Security Services

([Back](../README.md))

## Objective

Establish external and internal network perimeters and monitor network traffic.

## Applicable Service Models

- IaaS, PaaS, SaaS

## Mandatory Requirements

- Ensure that egress/ingress points to and from GC cloud-based environments are managed and monitored.
- Implement network boundary protection mechanisms for all external facing interfaces that enforce a deny-all or allow-by-exception policy.
- Perimeter security services such as boundary protection, intrusion prevention services, proxy services, TLS traffic inspection, etc. must be enabled based on risk profile, in alignment with GC Secure Connectivity Requirements and ITSP.80.022 and ITSG-38.
- Ensure that access to cloud storage services is protected and restricted to authorized security zones/network, users, and services.

## Validation

- Confirm policy for limiting number of public IPs.
- Confirm policy for network boundary protection.
- Confirm policy for limiting to authorized source IP addresses (e.g., GC IP addresses).
- Confirm that storage accounts are not exposed to the public.

## Additional Considerations

- Use centrally provisioned network security services where available.
- Confirm if the department is intending to establish dedicated and secure connections to on-premise resources.

## References

1. [SPIN 2017-01](https://www.canada.ca/en/treasury-board-secretariat/services/access-information-privacy/security-identity-management/direction-secure-use-commercial-cloud-services-spin.html), subsection 6.2.4
2. Refer to the network security zoning guidance in [ITSG-22](https://cyber.gc.ca/en/guidance/baseline-security-requirements-network-security-zones-government-canada-itsg-22) and [ITSG-38](https://cyber.gc.ca/en/guidance/network-security-zoning-design-considerations-placement-services-within-zones-itsg-38).
3. CSE Top 10 #1

Related security controls: AC-3, AC‑4, SC‑7, SC‑7(5), SI-4, SI-4(18)
