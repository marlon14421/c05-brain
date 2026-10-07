---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0058"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0058: SharePoint ToolShell Exploitation — Defensive Application

## Source record

- [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

The [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058) campaign was conducted in July 2025 and encompassed the first waves of exploitation against incompletely patched spoofing (CVE-2025-49706) and remote code execution (CVE-2025-49704) vulnerabilities affecting on-premises Microsoft SharePoint servers. Later patched and updated as CVE-2025-53770 and CVE-2025-53771, the ToolShell vulnerabilities were widely exploited including by China-based ransomware actor Storm-2603 and espionage actors [Threat Group-3390](https://attack.mitre.org/groups/G0027) and [ZIRCONIUM](https://attack.mitre.org/groups/G0128). [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058) targeted multiple regions and industries including finance, education, energy, and healthcare across Asia, Europe, and the United States.(Citation: Microsoft SharePoint Exploit JUL 2025)(Citation: Palo Alto SharePoint Vulnerabilities JUL 2025)(Citation: Eye Research ToolShell JUL 2025)(Citation: ESET ToolShell JUL 2025)(Citation: Trend Micro SharePoint Attacks JUL 2025)

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
