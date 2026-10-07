---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1030"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1030: Network Segmentation — Defensive Application

## Source record

- [[01 ATT&CK/M1030 - Network Segmentation|M1030 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Network segmentation involves dividing a network into smaller, isolated segments to control and limit the flow of traffic between devices, systems, and applications. By segmenting networks, organizations can reduce the attack surface, restrict lateral movement by adversaries, and protect critical assets from compromise. Effective network segmentation leverages a combination of physical boundaries, logical separation through VLANs, and access control policies enforced by network appliances like firewalls, routers, and cloud-based configurations. This mitigation can be implemented through the following measures: Segment Critical Systems: - Identify and group systems based on their function, sensitivity, and risk. Examples include payment systems, HR databases, production systems, and internet-facing servers. - Use VLANs, firewalls, or routers to enforce logical separation. Implement DMZ for Public-Facing Services: - Host web servers, DNS servers, and email servers in a DMZ to limit their access to internal systems. - Apply strict firewall rules to filter traffic between the DMZ and internal networks. Use Cloud-Based Segmentation: - In cloud environments, use VPCs, subnets, and security groups to isolate applications and enforce traffic rules. - Apply AWS Transit Gateway or Azure VNet peering for controlled connectivity between cloud segments. Apply Microsegmentation for Workloads: - Use software-defined networking (SDN) tools to implement workload-level segmentation and prevent lateral movement. Restrict Traffic with ACLs and Firewalls: - Apply Access Control Lists (ACLs) to network devices to enforce "deny by default" policies. - Use firewalls to restrict both north-south (external-internal) and east-west (internal-internal) traffic. Monitor and Audit Segmented Networks: - Regularly review firewall rules, ACLs, and segmentation policies. - Monitor network flows for anomalies to ensure segmentation is effective. Test Segmentation Effectiveness: - Perform periodic penetration tests to verify that unauthorized access is blocked between network segments.

## Defensive focus

Assess the control as an implementable safeguard with a defined owner, target population, configuration, exception path, and evidence of operation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets and versions support this control, and where are exceptions required?
- Does the control reduce the relevant exposure without disabling a legitimate business function?
- How is coverage measured and configuration drift detected?
- What compensating control applies where the primary safeguard is unavailable?
- What test demonstrates continued effectiveness after updates?

## Safe validation

Pilot configuration changes in a representative test group, obtain owner approval, and preserve a tested rollback plan. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
