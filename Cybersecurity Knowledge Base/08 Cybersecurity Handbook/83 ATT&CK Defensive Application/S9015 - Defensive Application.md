---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9015"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S9015: BRICKSTORM — Defensive Application

## Source record

- [[01 ATT&CK/S9015 - BRICKSTORM|S9015 source record]]
- ATT&CK class: Malware
- Platforms: ESXi, Linux, Network Devices, Windows
- Tactics: Not specified

## Source context

[BRICKSTORM](https://attack.mitre.org/software/S9015) is a cross-platform backdoor with variants written in Go and Rust that facilitates command and control, the ingress transfer of other malware, and the exfiltration of data.(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Picus Security BRICKSTORM UNC5221 October 2025)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)(Citation: Google BRICKSTORM September 2025) [BRICKSTORM](https://attack.mitre.org/software/S9015) has also been created from a .NET application using ahead-of-time (AOT) compilation to blend in within victim environments.(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026) [BRICKSTORM](https://attack.mitre.org/software/S9015) was first observed in April 2024.(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024) [BRICKSTORM](https://attack.mitre.org/software/S9015) has previously been leveraged by People's Republic of China (PRC) state-nexus actors identified as UNC6201, UNC5221, WARP PANDA, PunyToad, and SYLVANITE.(Citation: Cloudflare 2026 Threat Report New Threat Actors March 2026)(Citation: CrowdStrike BRICKSTORM WARP PANDA UNC5221 December 2025)(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Dragos SYLVANITE MuddyWater Electrum March 2026)(Citation: NVISO BRICKSTORM April 2025)(Citation: Google BRICKSTORM GRIMBOLT UNC5221 UNC6201 February 2026)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)(Citation: Google BRICKSTORM September 2025)

## Defensive focus

Use the record as contextual threat intelligence, not as attribution evidence or proof that a specific organization is targeted. Prioritize observable behaviors and relevant defensive exposure.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which source claims are independently supported, current, and relevant to this environment?
- Which behavior, platform, or dependency can be translated into a control or detection hypothesis?
- Are names, indicators, and reported relationships time-bounded and subject to reuse or reclassification?
- What local evidence would confirm or disconfirm the hypothesis?
- Which response steps protect evidence and avoid premature attribution?

## Safe validation

Use public reporting and sanitized lab data. Do not acquire or execute malware or tools from a catalog entry; use approved analysis procedures and isolated environments when necessary. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
