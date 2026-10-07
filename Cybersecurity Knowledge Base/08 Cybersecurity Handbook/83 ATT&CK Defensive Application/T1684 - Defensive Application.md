---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1684"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1684: Social Engineering — Defensive Application

## Source record

- [[01 ATT&CK/T1684 - Social Engineering|T1684 source record]]
- ATT&CK class: Technique
- Platforms: Linux, macOS, Office Suite, SaaS, Windows
- Tactics: stealth

## Source context

Adversaries may use social engineering techniques to influence users to take actions that result in unauthorized access, approval of changes, disclosure of sensitive information, or execution of adversary-supplied instructions (i.e., introduction of malicious payloads or software), while minimizing technical indicators. Adversaries may leverage trust-building methods across multiple channels (e.g., executive, vendor, or help desk scenarios, including AI-enabled voice interactions) to prompt user-authorized actions such as password resets, MFA changes, financial approvals, or the disclosure of sensitive information. Adversaries may also leverage common business communications and workflows such as email, collaboration platforms, voice communications, recruiting processes, help desk interactions, and SaaS consent mechanisms to make malicious requests appear routine and legitimate.(Citation: Proofpoint TA427 April 2024)(Citation: SE SentinelOne 2)(Citation: SE - Hackers Target Workday) Additionally, adversaries have persuaded victims to take actions through references of current events, harnessing relevant themes to the work role or the organizations mission. For example, adversaries may use scare tactics (i.e., threaten repercussions for non-compliance) or otherwise incite victims’ emotions in order to generate a sense of urgency to take action.(Citation: SE Proofpoint)(Citation: SE SentinelOne) This technique may include common social engineering patterns such as [Phishing](https://attack.mitre.org/techniques/T1566) and [Spearphishing Voice](https://attack.mitre.org/techniques/T1566/004), often supported by convincing and targeted narratives.(Citation: SE SentinelOne 2)(Citation: Fortinet Trends 25-26)

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
