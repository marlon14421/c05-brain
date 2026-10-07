---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "S9044"
attack_type: "Malware"
source: MITRE ATT&CK
---
# S9044: Kali365 — Defensive Application

## Source record

- [[01 ATT&CK/S9044 - Kali365|S9044 source record]]
- ATT&CK class: Malware
- Platforms: IaaS, macOS, Windows
- Tactics: Not specified

## Source context

[Kali365](https://attack.mitre.org/software/S9044) is a Phishing-as-a-Service (PHaaS) kit first observed in April 2026 that generates victim-targeted lures across multiple operating systems to induce users into copying and pasting actor-controlled commands for local execution.(Citation: Artic Wolf Labs Kali365 Device Code April 2026)(Citation: FBI IC3 Alert I-052126 Kali365 May 2026)(Citation: Huntress Kali365 Device Code June 2026)(Citation: SpyCloud Kali365 June 2026) [Kali365](https://attack.mitre.org/software/S9044) incorporates on-demand device code generation and mirrors the copy-paste execution tradecraft associated with ClickFix. (Citation: Huntress Kali365 Device Code June 2026) Operators have used [Kali365](https://attack.mitre.org/software/S9044) to harvest victims' OAuth tokens and session cookies through adversary-in-the-middle (AiTM) interception, enabling account takeover.(Citation: Artic Wolf Labs Kali365 Device Code April 2026)(Citation: Artic Wolf Kali365 Device Code OAuth June 2026)(Citation: FBI IC3 Alert I-052126 Kali365 May 2026)(Citation: Huntress Kali365 Device Code June 2026)(Citation: SpyCloud Kali365 June 2026) [Kali365](https://attack.mitre.org/software/S9044) PHaaS was first observed in April 2026.(Citation: Artic Wolf Labs Kali365 Device Code April 2026) [Kali365](https://attack.mitre.org/software/S9044) has also been affiliated with other branding to include Octopi365 and Freedom365.(Citation: Huntress Kali365 Device Code June 2026)

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
