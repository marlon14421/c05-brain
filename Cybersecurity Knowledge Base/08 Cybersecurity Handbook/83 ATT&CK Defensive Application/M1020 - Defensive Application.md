---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1020"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1020: SSL/TLS Inspection — Defensive Application

## Source record

- [[01 ATT&CK/M1020 - SSL-TLS Inspection|M1020 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

SSL/TLS inspection involves decrypting encrypted network traffic to examine its content for signs of malicious activity. This capability is crucial for detecting threats that use encryption to evade detection, such as phishing, malware, or data exfiltration. After inspection, the traffic is re-encrypted and forwarded to its destination. This mitigation can be implemented through the following measures: Deploy SSL/TLS Inspection Appliances: - Implement SSL/TLS inspection solutions to decrypt and inspect encrypted traffic. - Ensure appliances are placed at critical network choke points for maximum coverage. Configure Decryption Policies: - Define rules to decrypt traffic for specific applications, ports, or domains. - Avoid decrypting sensitive or privacy-related traffic, such as financial or healthcare websites, to comply with regulations. Integrate Threat Intelligence: - Use threat intelligence feeds to correlate inspected traffic with known indicators of compromise (IOCs). Integrate with Security Tools: - Combine SSL/TLS inspection with SIEM and NDR tools to analyze decrypted traffic and generate alerts for suspicious activity. - Example Tools: Splunk, Darktrace Implement Certificate Management: - Use trusted internal or third-party certificates for traffic re-encryption after inspection. - Regularly update certificate authorities (CAs) to ensure secure re-encryption. Monitor and Tune: - Continuously monitor SSL/TLS inspection logs for anomalies and fine-tune policies to reduce false positives.

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
