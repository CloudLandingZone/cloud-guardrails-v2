# Segment and Separate

([Back](../README.md))

## Objective

Segment and separate information based on sensitivity of information.

## Applicable Service Models

- IaaS, PaaS

## Mandatory Requirements

- Isolate and secure cloud workloads based on the sensitivity of the data.

## Validation

- Confirm that department has a target network architecture high level design and / or diagram with appropriate segmentation between network security zones in alignment with CSE’s ITSG-22 and ITSG-38.
- Confirm that the department has documented a deployment guide of the cloud platform and associated services. (The document is to capture landing zone if applicable)
- Confirm that CSP segmentation features are leveraged to provide segmentation of Management, Prod, UAT, DEV, and test. (For example, use of subscription, instances, or other cloud provider construct).

## Additional Considerations

- Develop a target network security design that considers segmentation via network security zones, in alignment with ITSG-22 and ITSG-38.
- Leverage landing zones that include pre-defined, secured, multi-account support to allow different workloads and teams to be onboarded in an automated manner.

## References

1. [SPIN 2017-01](https://www.canada.ca/en/treasury-board-secretariat/services/access-information-privacy/security-identity-management/direction-secure-use-commercial-cloud-services-spin.html), subsection 6.2.4
2. CSE Top 10 #5
3. Refer to the network security zoning guidance in [ITSG-22](https://cyber.gc.ca/en/guidance/baseline-security-requirements-network-security-zones-government-canada-itsg-22) and [ITSG-38](https://cyber.gc.ca/en/guidance/network-security-zoning-design-considerations-placement-services-within-zones-itsg-38).

Related security controls: AC‑4, SC‑7
