---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1647"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1647: Plist File Modification — Defensive Application

## Source record

- [[01 ATT&CK/T1647 - Plist File Modification|T1647 source record]]
- ATT&CK class: Technique
- Platforms: macOS
- Tactics: defense-impairment

## Source context

Adversaries may modify property list files (plist files) to enable other malicious activity, while also potentially evading and bypassing system defenses. macOS applications use plist files, such as the info.plist file, to store properties and configuration settings that inform the operating system how to handle the application at runtime. Plist files are structured metadata in key-value pairs formatted in XML based on Apple's Core Foundation DTD. Plist files can be saved in text or binary format.(Citation: fileinfo plist file description) Adversaries can modify key-value pairs in plist files to influence system behaviors, such as hiding the execution of an application (i.e. [Hidden Window](https://attack.mitre.org/techniques/T1564/003)) or running additional commands for persistence (ex: [Launch Agent](https://attack.mitre.org/techniques/T1543/001)/[Launch Daemon](https://attack.mitre.org/techniques/T1543/004) or [Re-opened Applications](https://attack.mitre.org/techniques/T1547/007)). For example, adversaries can add a malicious application path to the `~/Library/Preferences/com.apple.dock.plist` file, which controls apps that appear in the Dock. Adversaries can also modify the LSUIElement key in an application’s info.plist file to run the app in the background. Adversaries can also insert key-value pairs to insert environment variables, such as LSEnvironment , to enable persistence via [Dynamic Linker Hijacking](https://attack.mitre.org/techniques/T1574/006).(Citation: wardle chp2 persistence)(Citation: eset_osx_flashback)

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
