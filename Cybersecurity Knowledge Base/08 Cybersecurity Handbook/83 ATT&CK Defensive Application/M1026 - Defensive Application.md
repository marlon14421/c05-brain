---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1026"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1026: Privileged Account Management — Defensive Application

## Source record

- [[01 ATT&CK/M1026 - Privileged Account Management|M1026 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Privileged Account Management focuses on implementing policies, controls, and tools to securely manage privileged accounts (e.g., SYSTEM, root, or administrative accounts). This includes restricting access, limiting the scope of permissions, monitoring privileged account usage, and ensuring accountability through logging and auditing.This mitigation can be implemented through the following measures: Account Permissions and Roles: - Implement RBAC and least privilege principles to allocate permissions securely. - Use tools like Active Directory Group Policies to enforce access restrictions. Credential Security: - Deploy password vaulting tools like CyberArk, HashiCorp Vault, or KeePass for secure storage and rotation of credentials. - Enforce password policies for complexity, uniqueness, and expiration using tools like Microsoft Group Policy Objects (GPO). Multi-Factor Authentication (MFA): - Enforce MFA for all privileged accounts using Duo Security, Okta, or Microsoft Azure AD MFA. Privileged Access Management (PAM): - Use PAM solutions like CyberArk, BeyondTrust, or Thycotic to manage, monitor, and audit privileged access. Auditing and Monitoring: - Integrate activity monitoring into your SIEM (e.g., Splunk or QRadar) to detect and alert on anomalous privileged account usage. Just-In-Time Access: - Deploy JIT solutions like Azure Privileged Identity Management (PIM) or configure ephemeral roles in AWS and GCP to grant time-limited elevated permissions. *Tools for Implementation* Privileged Access Management (PAM): - CyberArk, BeyondTrust, Thycotic, HashiCorp Vault. Credential Management: - Microsoft LAPS (Local Admin Password Solution), Password Safe, HashiCorp Vault, KeePass. Multi-Factor Authentication: - Duo Security, Okta, Microsoft Azure MFA, Google Authenticator. Linux Privilege Management: - sudo configuration, SELinux, AppArmor. Just-In-Time Access: - Azure Privileged Identity Management (PIM), AWS IAM Roles with session constraints, GCP Identity-Aware Proxy.

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
