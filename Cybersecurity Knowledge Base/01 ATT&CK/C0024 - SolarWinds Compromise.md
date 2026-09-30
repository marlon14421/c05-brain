---
type: "Campaign"
source: MITRE ATT&CK
id: "C0024"
source_url: "https://attack.mitre.org/campaigns/C0024"
created: "2023-03-24"
modified: "2026-07-31"
---
# C0024: SolarWinds Compromise

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0024  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024) was a sophisticated supply chain cyber operation conducted by [APT29](https://attack.mitre.org/groups/G0016) that was discovered in mid-December 2020. [APT29](https://attack.mitre.org/groups/G0016) used customized malware to inject malicious code into the SolarWinds Orion software build process that was later distributed through a normal software update; they also used password spraying, token theft, API abuse, spear phishing, and other supply chain attacks to compromise user accounts and leverage their associated access. Victims of this campaign included government, consulting, technology, telecom, and other organizations in North America, Europe, Asia, and the Middle East. This activity has been labled the StellarParticle campaign in industry reporting.(Citation: CrowdStrike StellarParticle January 2022) Industry reporting also initially referred to the actors involved in this campaign as UNC2452, NOBELIUM, Dark Halo, and SolarStorm.(Citation: SolarWinds Advisory Dec 2020)(Citation: SolarWinds Sunburst Sunspot Update January 2021)(Citation: FireEye SUNBURST Backdoor December 2020)(Citation: Volexity SolarWinds)(Citation: CrowdStrike StellarParticle January 2022)(Citation: Unit 42 SolarStorm December 2020)(Citation: Microsoft Analyzing Solorigate Dec 2020)(Citation: Microsoft Internal Solorigate Investigation Blog) In April 2021, the US and UK governments attributed the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024) to Russia's Foreign Intelligence Service (SVR); public statements included citations to [APT29](https://attack.mitre.org/groups/G0016), Cozy Bear, and The Dukes.(Citation: NSA Joint Advisory SVR SolarWinds April 2021)(Citation: UK NSCS Russia SolarWinds April 2021)(Citation: Mandiant UNC2452 APT29 April 2022) The US government assessed that of the approximately 18,000 affected public and private sector customers of Solar Winds’ Orion product, a much smaller number were compromised by follow-on [APT29](https://attack.mitre.org/groups/G0016) activity on their systems.(Citation: USG Joint Statement SolarWinds January 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0024](https://attack.mitre.org/campaigns/C0024)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
