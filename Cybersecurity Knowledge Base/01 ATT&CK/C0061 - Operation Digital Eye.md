---
type: "Campaign"
source: MITRE ATT&CK
id: "C0061"
source_url: "https://attack.mitre.org/campaigns/C0061"
created: "2026-04-19"
modified: "2026-07-31"
---
# C0061: Operation Digital Eye

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0061  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Operation Digital Eye](https://attack.mitre.org/campaigns/C0061) was conducted in June and July of 2024 by suspected People's Republic of China (PRC)-nexus threat actors targeting business-to-business IT service providers in Southern Europe. [Operation Digital Eye](https://attack.mitre.org/campaigns/C0061) activity included the use of Visual Studio Code tunnels for command and control (C2) and custom lateral movement capabilities. Overlaps in tooling between Digital Eye and previous China-nexus campaigns, Operation Soft Cell and Operation Tainted Love, indicate the potential use of shared vendors or digital quartermasters.(Citation: sentinelone operationDigitalEye Dec 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0061](https://attack.mitre.org/campaigns/C0061)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
