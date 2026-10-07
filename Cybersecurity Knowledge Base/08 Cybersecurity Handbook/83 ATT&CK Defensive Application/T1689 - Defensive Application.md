---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1689"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1689: Downgrade Attack — Defensive Application

## Source record

- [[01 ATT&CK/T1689 - Downgrade Attack|T1689 source record]]
- ATT&CK class: Technique
- Platforms: macOS, Windows, Linux
- Tactics: defense-impairment

## Source context

Adversaries may downgrade or use a version of system features that may be outdated, vulnerable, and/or does not support updated security controls. Downgrade attacks typically take advantage of a system’s backward compatibility to force it into less secure modes of operation. Adversaries may downgrade and use various less-secure versions of features of a system, such as [Command and Scripting Interpreter](https://attack.mitre.org/techniques/T1059) or even network protocols that can be abused to enable [Adversary-in-the-Middle](https://attack.mitre.org/techniques/T1557) or [Network Sniffing](https://attack.mitre.org/techniques/T1040).(Citation: Praetorian TLS Downgrade Attack 2014) For example, [PowerShell](https://attack.mitre.org/techniques/T1059/001) versions 5+ includes Script Block Logging (SBL), which can record executed script content. However, adversaries may attempt to execute a previous version of PowerShell that does not support SBL with the intent to impair defenses while running malicious scripts that may have otherwise been detected.(Citation: CrowdStrike downgrade attack)(Citation: Google Cloud downgrade attack)(Citation: att_def_ps_logging) Adversaries may similarly target network traffic to downgrade from an encrypted HTTPS connection to an unsecured HTTP connection that exposes network data in clear text.(Citation: Targeted SSL Stripping Attacks Are Real)(Citation: CrowdStrike Downgrade attack 2) On Windows systems, adversaries may downgrade the boot manager to a vulnerable version that bypasses Secure Boot, granting the ability to disable various operating system security mechanisms.(Citation: SafeBreach)

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
