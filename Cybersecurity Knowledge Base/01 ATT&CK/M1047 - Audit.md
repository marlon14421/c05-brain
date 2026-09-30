---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1047"
source_url: "https://attack.mitre.org/mitigations/M1047"
created: "2019-06-11"
modified: "2026-05-12"
---
# M1047: Audit

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1047  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Auditing is the process of recording activity and systematically reviewing and analyzing the activity and system configurations. The primary purpose of auditing is to detect anomalies and identify potential threats or weaknesses in the environment. Proper auditing configurations can also help to meet compliance requirements. The process of auditing encompasses regular analysis of user behaviors and system logs in support of proactive security measures. Auditing is applicable to all systems used within an organization, from the front door of a building to accessing a file on a fileserver. It is considered more critical for regulated industries such as, healthcare, finance and government where compliance requirements demand stringent tracking of user and system activates.This mitigation can be implemented through the following measures: System Audit: - Use Case: Regularly assess system configurations to ensure compliance with organizational security policies. - Implementation: Use tools to scan for deviations from established benchmarks. Permission Audits: - Use Case: Review file and folder permissions to minimize the risk of unauthorized access or privilege escalation. - Implementation: Run access reviews to identify users or groups with excessive permissions. Software Audits: - Use Case: Identify outdated, unsupported, or insecure software that could serve as an attack vector. - Implementation: Use inventory and vulnerability scanning tools to detect outdated versions and recommend secure alternatives. Configuration Audits: - Use Case: Evaluate system and network configurations to ensure secure settings (e.g., disabled SMBv1, enabled MFA). - Implementation: Implement automated configuration scanning tools like SCAP (Security Content Automation Protocol) to identify non-compliant systems. Network Audits: - Use Case: Examine network traffic, firewall rules, and endpoint communications to identify unauthorized or insecure connections. - Implementation: Utilize tools such as Wireshark, or Zeek to monitor and log suspicious network behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1047](https://attack.mitre.org/mitigations/M1047)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
