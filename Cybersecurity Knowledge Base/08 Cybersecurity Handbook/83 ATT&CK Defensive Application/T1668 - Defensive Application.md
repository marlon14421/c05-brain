---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1668"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1668: Exclusive Control — Defensive Application

## Source record

- [[01 ATT&CK/T1668 - Exclusive Control|T1668 source record]]
- ATT&CK class: Technique
- Platforms: Linux, macOS, Windows
- Tactics: persistence

## Source context

Adversaries who successfully compromise a system may attempt to maintain persistence by “closing the door” behind them – in other words, by preventing other threat actors from initially accessing or maintaining a foothold on the same system. For example, adversaries may patch a vulnerable, compromised system(Citation: Mandiant-iab-control)(Citation: CERT AT Fortinent Ransomware 2025) to prevent other threat actors from leveraging that vulnerability in the future. They may “close the door” in other ways, such as disabling vulnerable services(Citation: sophos-multiple-attackers), stripping privileges from accounts(Citation: aquasec-postgres-processes), or removing other malware already on the compromised device.(Citation: fsecure-netsky) Hindering other threat actors may allow an adversary to maintain sole access to a compromised system or network. This prevents the threat actor from needing to compete with or even being removed themselves by other threat actors. It also reduces the “noise” in the environment, lowering the possibility of being caught and evicted by defenders. Finally, in the case of [Resource Hijacking](https://attack.mitre.org/techniques/T1496), leveraging a compromised device’s full power allows the threat actor to maximize profit.(Citation: sophos-multiple-attackers)

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
