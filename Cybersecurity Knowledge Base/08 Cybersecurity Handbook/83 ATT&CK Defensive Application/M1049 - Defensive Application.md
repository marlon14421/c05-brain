---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1049"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1049: Antivirus/Antimalware — Defensive Application

## Source record

- [[01 ATT&CK/M1049 - Antivirus-Antimalware|M1049 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Antivirus/Antimalware solutions utilize signatures, heuristics, and behavioral analysis to detect, block, and remediate malicious software, including viruses, trojans, ransomware, and spyware. These solutions continuously monitor endpoints and systems for known malicious patterns and suspicious behaviors that indicate compromise. Antivirus/Antimalware software should be deployed across all devices, with automated updates to ensure protection against the latest threats. This mitigation can be implemented through the following measures: Signature-Based Detection: - Implementation: Use predefined signatures to identify known malware based on unique patterns such as file hashes, byte sequences, or command-line arguments. This method is effective against known threats. - Use Case: When malware like "Emotet" is detected, its signature (such as a specific file hash) matches a known database of malicious software, triggering an alert and allowing immediate quarantine of the infected file. Heuristic-Based Detection: - Implementation: Deploy heuristic algorithms that analyze behavior and characteristics of files and processes to identify potential malware, even if it doesn’t match a known signature. - Use Case: If a program attempts to modify multiple critical system files or initiate suspicious network communications, heuristic analysis may flag it as potentially malicious, even if no specific malware signature is available. Behavioral Detection (Behavior Prevention): - Implementation: Use behavioral analysis to detect patterns of abnormal activities, such as unusual system calls, unauthorized file encryption, or attempts to escalate privileges. - Use Case: Behavioral analysis can detect ransomware attacks early by identifying behavior like mass file encryption, even before a specific ransomware signature has been identified. Real-Time Scanning: - Implementation: Enable real-time scanning to automatically inspect files and network traffic for signs of malware as they are accessed, downloaded, or executed. - Use Case: When a user downloads an email attachment, the antivirus solution scans the file in real-time, checking it against both signatures and heuristics to detect any malicious content before it can be opened. Cloud-Assisted Threat Intelligence: - Implementation: Use cloud-based threat intelligence to ensure the antivirus solution can access the latest malware definitions and real-time threat feeds from a global database of emerging threats. - Use Case: Cloud-assisted antivirus solutions quickly identify newly discovered malware by cross-referencing against global threat databases, providing real-time protection against zero-day attacks. **Tools for Implementation**: - Endpoint Security Platforms: Use solutions such as EDR for comprehensive antivirus/antimalware protection across all systems. - Centralized Management: Implement centralized antivirus management consoles that provide visibility into threat activity, enable policy enforcement, and automate updates. - Behavioral Analysis Tools: Leverage solutions with advanced behavioral analysis capabilities to detect malicious activity patterns that don’t rely on known signatures.

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
