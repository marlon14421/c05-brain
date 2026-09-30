---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1037"
source_url: "https://attack.mitre.org/mitigations/M1037"
created: "2019-06-11"
modified: "2026-05-12"
---
# M1037: Filter Network Traffic

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1037  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Employ network appliances and endpoint software to filter ingress, egress, and lateral network traffic. This includes protocol-based filtering, enforcing firewall rules, and blocking or restricting traffic based on predefined conditions to limit adversary movement and data exfiltration. This mitigation can be implemented through the following measures: Ingress Traffic Filtering: - Use Case: Configure network firewalls to allow traffic only from authorized IP addresses to public-facing servers. - Implementation: Limit SSH (port 22) and RDP (port 3389) traffic to specific IP ranges. Egress Traffic Filtering: - Use Case: Use firewalls or endpoint security software to block unauthorized outbound traffic to prevent data exfiltration and command-and-control (C2) communications. - Implementation: Block outbound traffic to known malicious IPs or regions where communication is unexpected. Protocol-Based Filtering: - Use Case: Restrict the use of specific protocols that are commonly abused by adversaries, such as SMB, RPC, or Telnet, based on business needs. - Implementation: Disable SMBv1 on endpoints to prevent exploits like EternalBlue. Network Segmentation: - Use Case: Create network segments for critical systems and restrict communication between segments unless explicitly authorized. - Implementation: Implement VLANs to isolate IoT devices or guest networks from core business systems. Application Layer Filtering: - Use Case: Use proxy servers or Web Application Firewalls (WAFs) to inspect and block malicious HTTP/S traffic. - Implementation: Configure a WAF to block SQL injection attempts or other web application exploitation techniques.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1037](https://attack.mitre.org/mitigations/M1037)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
