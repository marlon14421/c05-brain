---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1018"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1018: User Account Management — Defensive Application

## Source record

- [[01 ATT&CK/M1018 - User Account Management|M1018 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

User Account Management involves implementing and enforcing policies for the lifecycle of user accounts, including creation, modification, and deactivation. Proper account management reduces the attack surface by limiting unauthorized access, managing account privileges, and ensuring accounts are used according to organizational policies. This mitigation can be implemented through the following measures: Enforcing the Principle of Least Privilege - Implementation: Assign users only the minimum permissions required to perform their job functions. Regularly audit accounts to ensure no excess permissions are granted. - Use Case: Reduces the risk of privilege escalation by ensuring accounts cannot perform unauthorized actions. Implementing Strong Password Policies - Implementation: Enforce password complexity requirements (e.g., length, character types). Require password expiration every 90 days and disallow password reuse. - Use Case: Prevents adversaries from gaining unauthorized access through password guessing or brute force attacks. Managing Dormant and Orphaned Accounts - Implementation: Implement automated workflows to disable accounts after a set period of inactivity (e.g., 30 days). Remove orphaned accounts (e.g., accounts without an assigned owner) during regular account audits. - Use Case: Eliminates dormant accounts that could be exploited by attackers. Account Lockout Policies - Implementation: Configure account lockout thresholds (e.g., lock accounts after five failed login attempts). Set lockout durations to a minimum of 15 minutes. - Use Case: Mitigates automated attack techniques that rely on repeated login attempts. Multi-Factor Authentication (MFA) for High-Risk Accounts - Implementation: Require MFA for all administrative accounts and high-risk users. Use MFA mechanisms like hardware tokens, authenticator apps, or biometrics. - Use Case: Prevents unauthorized access, even if credentials are stolen. Restricting Interactive Logins - Implementation: Restrict interactive logins for privileged accounts to specific secure systems or management consoles. Use group policies to enforce logon restrictions. - Use Case: Protects sensitive accounts from misuse or exploitation. *Tools for Implementation* Built-in Tools: - Microsoft Active Directory (AD): Centralized account management and RBAC enforcement. - Group Policy Object (GPO): Enforce password policies, logon restrictions, and account lockout policies. Identity and Access Management (IAM) Tools: - Okta: Centralized user provisioning, MFA, and SSO integration. - Microsoft Azure Active Directory: Provides advanced account lifecycle management, role-based access, and conditional access policies. Privileged Account Management (PAM): - CyberArk, BeyondTrust, Thycotic: Manage and monitor privileged account usage, enforce session recording, and JIT access.

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
