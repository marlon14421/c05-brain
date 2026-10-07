---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1053"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1053: Data Backup — Defensive Application

## Source record

- [[01 ATT&CK/M1053 - Data Backup|M1053 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Data Backup involves taking and securely storing backups of data from end-user systems and critical servers. It ensures that data remains available in the event of system compromise, ransomware attacks, or other disruptions. Backup processes should include hardening backup systems, implementing secure storage solutions, and keeping backups isolated from the corporate network to prevent compromise during active incidents. This mitigation can be implemented through the following measures: Regular Backup Scheduling: - Use Case: Ensure timely and consistent backups of critical data. - Implementation: Schedule daily incremental backups and weekly full backups for all critical servers and systems. Immutable Backups: - Use Case: Protect backups from modification or deletion, even by attackers. - Implementation: Use write-once-read-many (WORM) storage for backups, preventing ransomware from encrypting or deleting backup files. Backup Encryption: - Use Case: Protect data integrity and confidentiality during transit and storage. - Implementation: Encrypt backups using strong encryption protocols (e.g., AES-256) before storing them in local, cloud, or remote locations. Offsite Backup Storage: - Use Case: Ensure data availability during physical disasters or onsite breaches. - Implementation: Use cloud-based solutions like AWS S3, Azure Backup, or physical offsite storage to maintain a copy of critical data. Backup Testing: - Use Case: Validate backup integrity and ensure recoverability. - Implementation: Regularly test data restoration processes to ensure that backups are not corrupted and can be recovered quickly.

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
