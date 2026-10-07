---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1195"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1195: Supply Chain Compromise — Defensive Application

## Source record

- [[01 ATT&CK/T1195 - Supply Chain Compromise|T1195 source record]]
- ATT&CK class: Technique
- Platforms: Linux, Windows, macOS, SaaS
- Tactics: initial-access

## Source context

Adversaries may manipulate products or product delivery mechanisms prior to receipt by a final consumer for the purpose of data or system compromise. Supply chain compromise can take place at any stage of the supply chain including: * Manipulation of development tools * Manipulation of a development environment * Manipulation of source code repositories (public or private) * Manipulation of source code in open-source dependencies * Manipulation of software update/distribution mechanisms * Compromised/infected system images (removable media infected at the factory)(Citation: IBM Storwize)(Citation: Schneider Electric USB Malware) * Replacement of legitimate software with modified versions * Sales of modified/counterfeit products to legitimate distributors * Shipment interdiction While supply chain compromise can impact any component of hardware or software, adversaries looking to gain execution have often focused on malicious additions to legitimate software in software distribution or update channels.(Citation: Avast CCleaner3 2018)(Citation: Microsoft Dofoil 2018)(Citation: Command Five SK 2011) Adversaries may limit targeting to a desired victim set or distribute malicious software to a broad set of consumers but only follow up with specific victims.(Citation: Symantec Elderwood Sept 2012)(Citation: Avast CCleaner3 2018)(Citation: Command Five SK 2011) Popular open-source projects that are used as dependencies in many applications may also be targeted as a means to add malicious code to users of the dependency.(Citation: Trendmicro NPM Compromise) In some cases, adversaries may conduct “second-order” supply chain compromises by leveraging the access gained from an initial supply chain compromise to further compromise a software component.(Citation: Krebs 3cx overview 2023) This may allow the threat actor to spread to even more victims.

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
