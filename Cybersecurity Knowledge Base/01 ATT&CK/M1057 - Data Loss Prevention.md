---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1057"
source_url: "https://attack.mitre.org/mitigations/M1057"
created: "2021-08-04"
modified: "2024-12-10"
---
# M1057: Data Loss Prevention

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1057  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Data Loss Prevention (DLP) involves implementing strategies and technologies to identify, categorize, monitor, and control the movement of sensitive data within an organization. This includes protecting data formats indicative of Personally Identifiable Information (PII), intellectual property, or financial data from unauthorized access, transmission, or exfiltration. DLP solutions integrate with network, endpoint, and cloud platforms to enforce security policies and prevent accidental or malicious data leaks. (Citation: PurpleSec Data Loss Prevention) This mitigation can be implemented through the following measures: Sensitive Data Categorization: - Use Case: Identify and classify data based on sensitivity (e.g., PII, financial data, trade secrets). - Implementation: Use DLP solutions to scan and tag files containing sensitive information using predefined patterns, such as Social Security Numbers or credit card details. Exfiltration Restrictions: - Use Case: Prevent unauthorized transmission of sensitive data. - Implementation: Enforce policies to block unapproved email attachments, unauthorized USB usage, or unencrypted data uploads to cloud storage. Data-in-Transit Monitoring: - Use Case: Detect and prevent the transmission of sensitive data over unapproved channels. - Implementation: Deploy network-based DLP tools to inspect outbound traffic for sensitive content (e.g., financial records or PII) and block unapproved transmissions. Endpoint Data Protection: - Use Case: Monitor and control sensitive data usage on endpoints. - Implementation: Use endpoint-based DLP agents to block copy-paste actions of sensitive data and unauthorized printing or file sharing. Cloud Data Security: - Use Case: Protect data stored in cloud platforms. - Implementation: Integrate DLP with cloud storage platforms like Google Drive, OneDrive, or AWS to monitor and restrict sensitive data sharing or downloads.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1057](https://attack.mitre.org/mitigations/M1057)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
