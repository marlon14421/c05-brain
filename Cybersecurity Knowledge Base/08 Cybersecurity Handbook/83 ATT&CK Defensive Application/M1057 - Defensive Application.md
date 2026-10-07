---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1057"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1057: Data Loss Prevention — Defensive Application

## Source record

- [[01 ATT&CK/M1057 - Data Loss Prevention|M1057 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Data Loss Prevention (DLP) involves implementing strategies and technologies to identify, categorize, monitor, and control the movement of sensitive data within an organization. This includes protecting data formats indicative of Personally Identifiable Information (PII), intellectual property, or financial data from unauthorized access, transmission, or exfiltration. DLP solutions integrate with network, endpoint, and cloud platforms to enforce security policies and prevent accidental or malicious data leaks. (Citation: PurpleSec Data Loss Prevention) This mitigation can be implemented through the following measures: Sensitive Data Categorization: - Use Case: Identify and classify data based on sensitivity (e.g., PII, financial data, trade secrets). - Implementation: Use DLP solutions to scan and tag files containing sensitive information using predefined patterns, such as Social Security Numbers or credit card details. Exfiltration Restrictions: - Use Case: Prevent unauthorized transmission of sensitive data. - Implementation: Enforce policies to block unapproved email attachments, unauthorized USB usage, or unencrypted data uploads to cloud storage. Data-in-Transit Monitoring: - Use Case: Detect and prevent the transmission of sensitive data over unapproved channels. - Implementation: Deploy network-based DLP tools to inspect outbound traffic for sensitive content (e.g., financial records or PII) and block unapproved transmissions. Endpoint Data Protection: - Use Case: Monitor and control sensitive data usage on endpoints. - Implementation: Use endpoint-based DLP agents to block copy-paste actions of sensitive data and unauthorized printing or file sharing. Cloud Data Security: - Use Case: Protect data stored in cloud platforms. - Implementation: Integrate DLP with cloud storage platforms like Google Drive, OneDrive, or AWS to monitor and restrict sensitive data sharing or downloads.

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
