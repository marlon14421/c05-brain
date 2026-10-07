---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1015"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1015: Active Directory Configuration — Defensive Application

## Source record

- [[01 ATT&CK/M1015 - Active Directory Configuration|M1015 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Implement robust Active Directory (AD) configurations using group policies to secure user accounts, control access, and minimize the attack surface. AD configurations enable centralized control over account settings, logon policies, and permissions, reducing the risk of unauthorized access and lateral movement within the network. This mitigation can be implemented through the following measures: Account Configuration: - Implementation: Use domain accounts instead of local accounts to leverage AD’s centralized management, including group policies, auditing, and access control. - Use Case: For IT staff managing shared resources, provision domain accounts that allow IT teams to log in centrally, reducing the risk of unmanaged, rogue local accounts on individual machines. Interactive Logon Restrictions: - Implementation: Configure group policies to restrict interactive logons (e.g., direct physical or RDP logons) for service accounts or privileged accounts that do not require such access. - Use Case: Prevent service accounts, such as SQL Server accounts, from having interactive logon privileges. This reduces the risk of these accounts being leveraged for lateral movement if compromised. Remote Desktop Settings: - Implementation: Limit Remote Desktop Protocol (RDP) access to specific, authorized accounts. Use group policies to enforce this, allowing only necessary users to establish RDP sessions. - Use Case: On sensitive servers (e.g., domain controllers or financial databases), restrict RDP access to administrative accounts only, while all other users are denied access. Dedicated Administrative Accounts: - Implementation: Create domain-wide administrative accounts that are restricted from interactive logons, designed solely for high-level tasks (e.g., software installation, patching). - Use Case: Create separate administrative accounts for different purposes, such as one set of accounts for installations and another for managing repository access. This limits exposure and helps reduce attack vectors. Authentication Silos: - Implementation: Configure Authentication Silos in AD, using group policies to create access zones with restrictions based on membership, such as the Protected Users security group. This restricts access to critical accounts and minimizes exposure to potential threats. - Use Case: Place high-risk or high-value accounts, such as executive or administrative accounts, in an Authentication Silo with extra controls, limiting their exposure to only necessary systems. This reduces the risk of credential misuse or abuse if these accounts are compromised. **Tools for Implementation**: - Active Directory Group Policies: Use Group Policy Management Console (GPMC) to configure, deploy, and enforce policies across AD environments. - PowerShell: Automate account configuration, logon restrictions, and policy application using PowerShell scripts. - AD Administrative Center: Manage Authentication Silos and configure high-level policies for critical user groups within AD.

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
