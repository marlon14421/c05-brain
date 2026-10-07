---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1036"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1036: Account Use Policies — Defensive Application

## Source record

- [[01 ATT&CK/M1036 - Account Use Policies|M1036 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Account Use Policies help mitigate unauthorized access by configuring and enforcing rules that govern how and when accounts can be used. These policies include enforcing account lockout mechanisms, restricting login times, and setting inactivity timeouts. Proper configuration of these policies reduces the risk of brute-force attacks, credential theft, and unauthorized access by limiting the opportunities for malicious actors to exploit accounts. This mitigation can be implemented through the following measures: Account Lockout Policies: - Implementation: Configure account lockout settings so that after a defined number of failed login attempts (e.g., 3-5 attempts), the account is locked for a specific time period (e.g., 15 minutes) or requires an administrator to unlock it. - Use Case: This prevents brute-force attacks by limiting how many incorrect password attempts can be made before the account is temporarily disabled, reducing the likelihood of an attacker successfully guessing a password. Login Time Restrictions: - Implementation: Set up login time policies to restrict when users or groups can log into systems. For example, only allowing login during standard business hours (e.g., 8 AM to 6 PM) for non-administrative accounts. - Use Case: This prevents unauthorized access outside of approved working hours, where login attempts might be more suspicious or harder to monitor. For example, if an account that is only supposed to be active during the day logs in at 2 AM, it should raise an alert or be blocked. Inactivity Timeout and Session Termination: - Implementation: Enforce session timeouts after a period of inactivity (e.g., 10-15 minutes) and require users to re-authenticate if they wish to resume the session. - Use Case: This policy prevents attackers from hijacking active sessions left unattended. For example, if an employee walks away from their computer without locking it, an attacker with physical access to the system would be unable to exploit the session. Password Aging Policies: - Implementation: Enforce password aging rules, requiring users to change their passwords after a defined period (e.g., 90 days) and ensure passwords are not reused by maintaining a password history. - Use Case: This limits the risk of compromised passwords being used indefinitely. Regular password changes make it more difficult for attackers to reuse stolen credentials. Account Expiration and Deactivation: - Implementation: Configure user accounts, especially for temporary or contract workers, to automatically expire after a set date or event. Accounts that remain unused for a specific period should be deactivated automatically. - Use Case: This prevents dormant accounts from becoming an attack vector. For example, an attacker can exploit unused accounts if they are not properly monitored or deactivated. **Tools for Implementation**: - Group Policy Objects (GPOs) in Windows: To enforce account lockout thresholds, login time restrictions, session timeouts, and password policies. - Identity and Access Management (IAM) solutions: For centralized management of user accounts, session policies, and automated deactivation of accounts. - Security Information and Event Management (SIEM) platforms: To monitor and alert on unusual login activity, such as failed logins or out-of-hours access attempts. - Multi-Factor Authentication (MFA) Tools: To further enforce secure login attempts, preventing brute-force or credential stuffing attacks.

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
