---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "C0024"
attack_type: "Campaign"
source: MITRE ATT&CK
---
# C0024: SolarWinds Compromise — Defensive Application

## Source record

- [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024 source record]]
- ATT&CK class: Campaign
- Platforms: Not specified
- Tactics: Not specified

## Source context

The [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024) was a sophisticated supply chain cyber operation conducted by [APT29](https://attack.mitre.org/groups/G0016) that was discovered in mid-December 2020. [APT29](https://attack.mitre.org/groups/G0016) used customized malware to inject malicious code into the SolarWinds Orion software build process that was later distributed through a normal software update; they also used password spraying, token theft, API abuse, spear phishing, and other supply chain attacks to compromise user accounts and leverage their associated access. Victims of this campaign included government, consulting, technology, telecom, and other organizations in North America, Europe, Asia, and the Middle East. This activity has been labled the StellarParticle campaign in industry reporting.(Citation: CrowdStrike StellarParticle January 2022) Industry reporting also initially referred to the actors involved in this campaign as UNC2452, NOBELIUM, Dark Halo, and SolarStorm.(Citation: SolarWinds Advisory Dec 2020)(Citation: SolarWinds Sunburst Sunspot Update January 2021)(Citation: FireEye SUNBURST Backdoor December 2020)(Citation: Volexity SolarWinds)(Citation: CrowdStrike StellarParticle January 2022)(Citation: Unit 42 SolarStorm December 2020)(Citation: Microsoft Analyzing Solorigate Dec 2020)(Citation: Microsoft Internal Solorigate Investigation Blog) In April 2021, the US and UK governments attributed the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024) to Russia's Foreign Intelligence Service (SVR); public statements included citations to [APT29](https://attack.mitre.org/groups/G0016), Cozy Bear, and The Dukes.(Citation: NSA Joint Advisory SVR SolarWinds April 2021)(Citation: UK NSCS Russia SolarWinds April 2021)(Citation: Mandiant UNC2452 APT29 April 2022) The US government assessed that of the approximately 18,000 affected public and private sector customers of Solar Winds’ Orion product, a much smaller number were compromised by follow-on [APT29](https://attack.mitre.org/groups/G0016) activity on their systems.(Citation: USG Joint Statement SolarWinds January 2021)

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
