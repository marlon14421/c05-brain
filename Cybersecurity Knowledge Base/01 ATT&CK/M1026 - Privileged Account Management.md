---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1026"
source_url: "https://attack.mitre.org/mitigations/M1026"
created: "2019-06-06"
modified: "2024-12-18"
---
# M1026: Privileged Account Management

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1026  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Privileged Account Management focuses on implementing policies, controls, and tools to securely manage privileged accounts (e.g., SYSTEM, root, or administrative accounts). This includes restricting access, limiting the scope of permissions, monitoring privileged account usage, and ensuring accountability through logging and auditing.This mitigation can be implemented through the following measures: Account Permissions and Roles: - Implement RBAC and least privilege principles to allocate permissions securely. - Use tools like Active Directory Group Policies to enforce access restrictions. Credential Security: - Deploy password vaulting tools like CyberArk, HashiCorp Vault, or KeePass for secure storage and rotation of credentials. - Enforce password policies for complexity, uniqueness, and expiration using tools like Microsoft Group Policy Objects (GPO). Multi-Factor Authentication (MFA): - Enforce MFA for all privileged accounts using Duo Security, Okta, or Microsoft Azure AD MFA. Privileged Access Management (PAM): - Use PAM solutions like CyberArk, BeyondTrust, or Thycotic to manage, monitor, and audit privileged access. Auditing and Monitoring: - Integrate activity monitoring into your SIEM (e.g., Splunk or QRadar) to detect and alert on anomalous privileged account usage. Just-In-Time Access: - Deploy JIT solutions like Azure Privileged Identity Management (PIM) or configure ephemeral roles in AWS and GCP to grant time-limited elevated permissions. *Tools for Implementation* Privileged Access Management (PAM): - CyberArk, BeyondTrust, Thycotic, HashiCorp Vault. Credential Management: - Microsoft LAPS (Local Admin Password Solution), Password Safe, HashiCorp Vault, KeePass. Multi-Factor Authentication: - Duo Security, Okta, Microsoft Azure MFA, Google Authenticator. Linux Privilege Management: - sudo configuration, SELinux, AppArmor. Just-In-Time Access: - Azure Privileged Identity Management (PIM), AWS IAM Roles with session constraints, GCP Identity-Aware Proxy.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1026](https://attack.mitre.org/mitigations/M1026)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
