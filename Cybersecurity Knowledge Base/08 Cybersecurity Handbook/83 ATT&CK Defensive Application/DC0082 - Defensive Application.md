---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "DC0082"
attack_type: "Data Component"
source: MITRE ATT&CK
---
# DC0082: Network Connection Creation — Defensive Application

## Source record

- [[01 ATT&CK/DC0082 - Network Connection Creation|DC0082 source record]]
- ATT&CK class: Data Component
- Platforms: Not specified
- Tactics: Not specified

## Source context

The initial establishment of a network session, where a system or process initiates a connection to a local or remote endpoint. This typically involves capturing socket information (source/destination IP, ports, protocol) and tracking session metadata. Monitoring these events helps detect lateral movement, exfiltration, and command-and-control (C2) activities. *Data Collection Measures:* - Windows: - Event ID 5156 – Filtering Platform Connection - Logs network connections permitted by Windows Filtering Platform (WFP). - Sysmon Event ID 3 – Network Connection Initiated - Captures process, source/destination IP, ports, and parent process. - Linux/macOS: - Netfilter (iptables), nftables logs - Tracks incoming and outgoing network connections. - AuditD (`connect` syscall) - Logs TCP, UDP, and ICMP connections. - Zeek (`conn.log`) - Captures protocol, duration, and bytes transferred. - Cloud & Network Infrastructure: - AWS VPC Flow Logs / Azure NSG Flow Logs - Logs IP traffic at the network level in cloud environments. - Zeek (conn.log) or Suricata (network events) - Captures packet metadata for detection and correlation. - Endpoint Detection & Response (EDR): - Detect anomalous network activity such as new C2 connections or data exfiltration attempts.

## Defensive focus

Evaluate whether this telemetry component supplies timely and trustworthy evidence for a stated defensive question while respecting privacy and retention limits.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which platform and event sources generate the data, and are they enabled throughout the target population?
- Are timestamps, identities, and fields reliable enough for the intended analytic?
- What collection gaps, sampling, or parser changes could weaken conclusions?
- Which sensitive fields need minimization or access restrictions?
- How are retention, integrity, and responder access governed?

## Safe validation

Validate collection with benign, expected events on owned systems and synthetic accounts. Document missing sources and do not infer absence of behavior from absent telemetry. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
