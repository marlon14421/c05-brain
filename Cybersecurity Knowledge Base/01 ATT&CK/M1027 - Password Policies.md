---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1027"
source_url: "https://attack.mitre.org/mitigations/M1027"
created: "2019-06-06"
modified: "2024-12-18"
---
# M1027: Password Policies

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1027  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Set and enforce secure password policies for accounts to reduce the likelihood of unauthorized access. Strong password policies include enforcing password complexity, requiring regular password changes, and preventing password reuse. This mitigation can be implemented through the following measures: Windows Systems: - Use Group Policy Management Console (GPMC) to configure: - Minimum password length (e.g., 12+ characters). - Password complexity requirements. - Password history (e.g., disallow last 24 passwords). - Account lockout duration and thresholds. Linux Systems: - Configure Pluggable Authentication Modules (PAM): - Use `pam_pwquality` to enforce complexity and length requirements. - Implement `pam_tally2` or `pam_faillock` for account lockouts. - Use `pwunconv` to disable password reuse. Password Managers: - Enforce usage of enterprise password managers (e.g., Bitwarden, 1Password, LastPass) to generate and store strong passwords. Password Blacklisting: - Use tools like Have I Been Pwned password checks or NIST-based blacklist solutions to prevent users from setting compromised passwords. Regular Auditing: - Periodically audit password policies and account configurations to ensure compliance using tools like LAPS (Local Admin Password Solution) and vulnerability scanners. *Tools for Implementation* Windows: - Group Policy Management Console (GPMC): Enforce password policies. - Microsoft Local Administrator Password Solution (LAPS): Enforce random, unique admin passwords. Linux/macOS: - PAM Modules (pam_pwquality, pam_tally2, pam_faillock): Enforce password rules. - Lynis: Audit password policies and system configurations. Cross-Platform: - Password Managers (Bitwarden, 1Password, KeePass): Manage and enforce strong passwords. - Have I Been Pwned API: Prevent the use of breached passwords. - NIST SP 800-63B compliant tools: Enforce password guidelines and blacklisting.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1027](https://attack.mitre.org/mitigations/M1027)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
