---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1682"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1682: Query Public AI Services — Defensive Application

## Source record

- [[01 ATT&CK/T1682 - Query Public AI Services|T1682 source record]]
- ATT&CK class: Technique
- Platforms: PRE
- Tactics: reconnaissance

## Source context

Adversaries may query publicly accessible artificial intelligence (AI) services, such as large language models (LLMs), to support targeting and operations. In addition to searching websites or databases directly (i.e., [Search Open Websites/Domains](https://attack.mitre.org/techniques/T1593)), adversaries may use AI services to synthesize, aggregate, and analyze publicly available information at scale. This may include identifying individuals or organizations to target, researching organizational structures and personnel, identifying technologies used by target organizations, researching business relationships to develop plausible pretexts for [Social Engineering](https://attack.mitre.org/techniques/T1684) approaches, identifying contact information for use in [Phishing](https://attack.mitre.org/techniques/T1566) or [Phishing for Information](https://attack.mitre.org/techniques/T1598), or gathering derogatory or sensitive information about individuals that may be used for extortion or coercion.(Citation: MSFT-AI)(Citation: GTIG AI Threat Tracker) Information gathered through AI services may be leveraged for other behaviors, such as establishing operational resources (i.e., [Generate Content](https://attack.mitre.org/techniques/T1683) or [Establish Accounts](https://attack.mitre.org/techniques/T1585). For obtaining access to AI tools and services, see [Artificial Intelligence](https://attack.mitre.org/techniques/T1588/007).

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
