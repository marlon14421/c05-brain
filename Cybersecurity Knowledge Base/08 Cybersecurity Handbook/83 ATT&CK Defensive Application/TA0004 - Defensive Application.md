---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "TA0004"
attack_type: "Tactic"
source: MITRE ATT&CK
---
# TA0004: Privilege Escalation — Defensive Application

## Source record

- [[01 ATT&CK/TA0004 - Privilege Escalation|TA0004 source record]]
- ATT&CK class: Tactic
- Platforms: Not specified
- Tactics: Not specified

## Source context

The adversary is trying to gain higher-level permissions. Privilege Escalation consists of techniques that adversaries use to gain higher-level permissions on a system or network. Adversaries can often enter and explore a network with unprivileged access but require elevated permissions to follow through on their objectives. Common approaches are to take advantage of system weaknesses, misconfigurations, and vulnerabilities. Examples of elevated access include: * SYSTEM/root level * local administrator * user account with admin-like access * user accounts with access to specific system or perform specific function These techniques often overlap with Persistence techniques, as OS features that let an adversary persist can execute in an elevated context.

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
