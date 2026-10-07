---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "T1665"
attack_type: "Technique"
source: MITRE ATT&CK
---
# T1665: Hide Infrastructure — Defensive Application

## Source record

- [[01 ATT&CK/T1665 - Hide Infrastructure|T1665 source record]]
- ATT&CK class: Technique
- Platforms: ESXi, Linux, macOS, Network Devices, Windows
- Tactics: command-and-control

## Source context

Adversaries may manipulate network traffic in order to hide and evade detection of their C2 infrastructure. This can be accomplished by identifying and filtering traffic from defensive tools,(Citation: TA571) masking malicious domains to obfuscate the true destination from both automated scanning tools and security researchers,(Citation: Schema-abuse)(Citation: Facad1ng)(Citation: Browser-updates) and otherwise hiding malicious artifacts to delay discovery and prolong the effectiveness of adversary infrastructure that could otherwise be identified, blocked, or taken down entirely. C2 networks may include the use of [Proxy](https://attack.mitre.org/techniques/T1090) or VPNs to disguise IP addresses, which can allow adversaries to blend in with normal network traffic and bypass conditional access policies or anti-abuse protections. For example, an adversary may use a virtual private cloud to spoof their IP address to closer align with a victim's IP address ranges. This may also bypass security measures relying on geolocation of the source IP address.(Citation: sysdig)(Citation: Orange Residential Proxies) Adversaries may also attempt to filter network traffic in order to evade defensive tools in numerous ways, including blocking/redirecting common incident responder or security appliance user agents.(Citation: mod_rewrite)(Citation: SocGholish-update) Filtering traffic based on IP and geo-fencing may also avoid automated sandboxing or researcher activity (i.e., [Virtualization/Sandbox Evasion](https://attack.mitre.org/techniques/T1497)).(Citation: TA571)(Citation: mod_rewrite) Hiding C2 infrastructure may also be supported by [Resource Development](https://attack.mitre.org/tactics/TA0042) activities such as [Acquire Infrastructure](https://attack.mitre.org/techniques/T1583) and [Compromise Infrastructure](https://attack.mitre.org/techniques/T1584). For example, using widely trusted hosting services or domains such as prominent URL shortening providers or marketing services for C2 networks may enable adversaries to present benign content that later redirects victims to malicious web pages or infrastructure once specific conditions are met.(Citation: StarBlizzard)(Citation: QR-cofense)

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
