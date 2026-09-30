---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1041"
source_url: "https://attack.mitre.org/mitigations/M1041"
created: "2019-06-11"
modified: "2025-04-02"
---
# M1041: Encrypt Sensitive Information

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1041  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Protect sensitive information at rest, in transit, and during processing by using strong encryption algorithms. Encryption ensures the confidentiality and integrity of data, preventing unauthorized access or tampering. This mitigation can be implemented through the following measures: Encrypt Data at Rest: - Use Case: Use full-disk encryption or file-level encryption to secure sensitive data stored on devices. - Implementation: Implement BitLocker for Windows systems or FileVault for macOS devices to encrypt hard drives. Encrypt Data in Transit: - Use Case: Use secure communication protocols (e.g., TLS, HTTPS) to encrypt sensitive data as it travels over networks. - Implementation: Enable HTTPS for all web applications and configure mail servers to enforce STARTTLS for email encryption. Encrypt Backups: - Use Case: Ensure that backup data is encrypted both during storage and transfer to prevent unauthorized access. - Implementation: Encrypt cloud backups using AES-256 before uploading them to Amazon S3 or Google Cloud. Encrypt Application Secrets: - Use Case: Store sensitive credentials, API keys, and configuration files in encrypted vaults. - Implementation: Use HashiCorp Vault or AWS Secrets Manager to manage and encrypt secrets. Database Encryption: - Use Case: Enable Transparent Data Encryption (TDE) or column-level encryption in database management systems. - Implementation: Use MySQL’s built-in encryption features to encrypt sensitive database fields such as social security numbers.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1041](https://attack.mitre.org/mitigations/M1041)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
