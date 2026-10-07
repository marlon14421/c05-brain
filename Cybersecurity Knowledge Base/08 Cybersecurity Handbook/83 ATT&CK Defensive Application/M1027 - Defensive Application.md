---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1027"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1027: Password Policies — Defensive Application

## Source record

- [[01 ATT&CK/M1027 - Password Policies|M1027 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Set and enforce secure password policies for accounts to reduce the likelihood of unauthorized access. Strong password policies include enforcing password complexity, requiring regular password changes, and preventing password reuse. This mitigation can be implemented through the following measures: Windows Systems: - Use Group Policy Management Console (GPMC) to configure: - Minimum password length (e.g., 12+ characters). - Password complexity requirements. - Password history (e.g., disallow last 24 passwords). - Account lockout duration and thresholds. Linux Systems: - Configure Pluggable Authentication Modules (PAM): - Use `pam_pwquality` to enforce complexity and length requirements. - Implement `pam_tally2` or `pam_faillock` for account lockouts. - Use `pwunconv` to disable password reuse. Password Managers: - Enforce usage of enterprise password managers (e.g., Bitwarden, 1Password, LastPass) to generate and store strong passwords. Password Blacklisting: - Use tools like Have I Been Pwned password checks or NIST-based blacklist solutions to prevent users from setting compromised passwords. Regular Auditing: - Periodically audit password policies and account configurations to ensure compliance using tools like LAPS (Local Admin Password Solution) and vulnerability scanners. *Tools for Implementation* Windows: - Group Policy Management Console (GPMC): Enforce password policies. - Microsoft Local Administrator Password Solution (LAPS): Enforce random, unique admin passwords. Linux/macOS: - PAM Modules (pam_pwquality, pam_tally2, pam_faillock): Enforce password rules. - Lynis: Audit password policies and system configurations. Cross-Platform: - Password Managers (Bitwarden, 1Password, KeePass): Manage and enforce strong passwords. - Have I Been Pwned API: Prevent the use of breached passwords. - NIST SP 800-63B compliant tools: Enforce password guidelines and blacklisting.

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
