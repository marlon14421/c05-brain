---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1098"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1098: Account Manipulation — Defensive Application

## Source record

- [[01 ATT&CK/T1098 - Account Manipulation|T1098 source record]]
- ATT&CK class: Technique
- Platforms: Containers, ESXi, IaaS, Identity Provider, Linux, macOS, Network Devices, Office Suite, SaaS, Windows
- Tactics: persistence, privilege-escalation

## Source context

Adversaries may manipulate accounts to maintain and/or elevate access to victim systems. Account manipulation may consist of any action that preserves or modifies adversary access to a compromised account, such as modifying credentials or permission groups.(Citation: FireEye SMOKEDHAM June 2021) These actions could also include account activity designed to subvert security policies, such as performing iterative password updates to bypass password duration policies and preserve the life of compromised credentials. In order to create or manipulate accounts, the adversary must already have sufficient permissions on systems or the domain. However, account manipulation may also lead to privilege escalation where modifications grant access to additional roles, permissions, or higher-privileged [Valid Accounts](https://attack.mitre.org/techniques/T1078).

## Defensive focus

Map the recorded behavior or objective to assets, trust boundaries, identities, and defensive controls in the local environment. ATT&CK classification alone does not establish activity or compromise.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets, roles, platforms, and business services are actually exposed to this behavior?
- What prevention or hardening control applies, and which owner maintains it?
- Which telemetry source can support or refute the behavior, and what blind spots remain?
- What legitimate administrative or software behavior could look similar?
- What containment or recovery decision is authorized if evidence is confirmed?

## Safe validation

Use an isolated lab, benign simulation, or sanitized historical data. Test only owned or explicitly authorized systems; do not reproduce harmful behavior against production targets. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
