---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1029"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1029: Remote Data Storage — Defensive Application

## Source record

- [[01 ATT&CK/M1029 - Remote Data Storage|M1029 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Remote Data Storage focuses on moving critical data, such as security logs and sensitive files, to secure, off-host locations to minimize unauthorized access, tampering, or destruction by adversaries. By leveraging remote storage solutions, organizations enhance the protection of forensic evidence, sensitive information, and monitoring data. This mitigation can be implemented through the following measures: Centralized Log Management: - Configure endpoints to forward security logs to a centralized log collector or SIEM. - Use tools like Splunk Graylog, or Security Onion to aggregate and store logs. - Example command (Linux): `sudo auditd | tee /var/log/audit/audit.log | nc 514` Remote File Storage Solutions: - Utilize cloud storage solutions like AWS S3, Google Cloud Storage, or Azure Blob Storage for sensitive data. - Ensure proper encryption at rest and access control policies (IAM roles, ACLs). Intrusion Detection Log Forwarding: - Forward logs from IDS/IPS systems (e.g., Zeek/Suricata) to a remote security information system. - Example for Suricata log forwarding: `outputs: - type: syslog protocol: tls address: ` Immutable Backup Configurations: - Enable immutable storage settings for backups to prevent adversaries from modifying or deleting data. - Example: AWS S3 Object Lock. Data Encryption: - Ensure encryption for sensitive data using AES-256 at rest and TLS 1.2+ for data in transit. Tools: OpenSSL, BitLocker, LUKS for Linux.

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
