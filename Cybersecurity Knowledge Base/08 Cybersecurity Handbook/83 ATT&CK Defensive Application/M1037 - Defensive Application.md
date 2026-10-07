---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1037"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1037: Filter Network Traffic — Defensive Application

## Source record

- [[01 ATT&CK/M1037 - Filter Network Traffic|M1037 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Employ network appliances and endpoint software to filter ingress, egress, and lateral network traffic. This includes protocol-based filtering, enforcing firewall rules, and blocking or restricting traffic based on predefined conditions to limit adversary movement and data exfiltration. This mitigation can be implemented through the following measures: Ingress Traffic Filtering: - Use Case: Configure network firewalls to allow traffic only from authorized IP addresses to public-facing servers. - Implementation: Limit SSH (port 22) and RDP (port 3389) traffic to specific IP ranges. Egress Traffic Filtering: - Use Case: Use firewalls or endpoint security software to block unauthorized outbound traffic to prevent data exfiltration and command-and-control (C2) communications. - Implementation: Block outbound traffic to known malicious IPs or regions where communication is unexpected. Protocol-Based Filtering: - Use Case: Restrict the use of specific protocols that are commonly abused by adversaries, such as SMB, RPC, or Telnet, based on business needs. - Implementation: Disable SMBv1 on endpoints to prevent exploits like EternalBlue. Network Segmentation: - Use Case: Create network segments for critical systems and restrict communication between segments unless explicitly authorized. - Implementation: Implement VLANs to isolate IoT devices or guest networks from core business systems. Application Layer Filtering: - Use Case: Use proxy servers or Web Application Firewalls (WAFs) to inspect and block malicious HTTP/S traffic. - Implementation: Configure a WAF to block SQL injection attempts or other web application exploitation techniques.

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
