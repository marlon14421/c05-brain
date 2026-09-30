---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0082"
source_url: "https://attack.mitre.org/datacomponents/DC0082"
created: "2021-10-20"
modified: "2026-05-12"
---
# DC0082: Network Connection Creation

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0082  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The initial establishment of a network session, where a system or process initiates a connection to a local or remote endpoint. This typically involves capturing socket information (source/destination IP, ports, protocol) and tracking session metadata. Monitoring these events helps detect lateral movement, exfiltration, and command-and-control (C2) activities. *Data Collection Measures:* - Windows: - Event ID 5156 – Filtering Platform Connection - Logs network connections permitted by Windows Filtering Platform (WFP). - Sysmon Event ID 3 – Network Connection Initiated - Captures process, source/destination IP, ports, and parent process. - Linux/macOS: - Netfilter (iptables), nftables logs - Tracks incoming and outgoing network connections. - AuditD (`connect` syscall) - Logs TCP, UDP, and ICMP connections. - Zeek (`conn.log`) - Captures protocol, duration, and bytes transferred. - Cloud & Network Infrastructure: - AWS VPC Flow Logs / Azure NSG Flow Logs - Logs IP traffic at the network level in cloud environments. - Zeek (conn.log) or Suricata (network events) - Captures packet metadata for detection and correlation. - Endpoint Detection & Response (EDR): - Detect anomalous network activity such as new C2 connections or data exfiltration attempts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0082](https://attack.mitre.org/datacomponents/DC0082)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
