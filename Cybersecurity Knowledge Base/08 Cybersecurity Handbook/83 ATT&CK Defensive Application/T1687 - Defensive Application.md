---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1687"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1687: Exploitation for Defense Impairment — Defensive Application

## Source record

- [[01 ATT&CK/T1687 - Exploitation for Defense Impairment|T1687 source record]]
- ATT&CK class: Technique
- Platforms: IaaS, Linux, macOS, SaaS, Windows
- Tactics: defense-impairment

## Source context

Adversaries may exploit vulnerabilities in security software, infrastructure, or defensive components to degrade, disable, or otherwise continue to impair their ability to prevent, detect, or respond to malicious activity. Adversaries may exploit a system or application vulnerability to directly interfere with defensive mechanisms. Exploitation occurs when an adversary takes advantage of a programming error in software, services, or the operating system to execute adversary-controlled code, often with the goal of weakening or disabling protections. Vulnerabilities may exist in security tools such as antivirus, endpoint detection and response (EDR), firewalls, or other monitoring solutions. Adversaries may use prior reconnaissance or perform discovery activities (e.g., [Software Discovery](https://attack.mitre.org/techniques/T1518)) to identify defensive tools present in an environment and target them for exploitation. Successful exploitation may allow adversaries to terminate security processes, disable protections, bypass enforcement mechanisms, or reduce the effectiveness of defensive controls. In some cases, vulnerabilities in cloud-based or SaaS infrastructure may also be leveraged to bypass built-in security boundaries or disrupt visibility and enforcement across environments.(Citation: Salesforce zero-day in facebook phishing attack)

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
