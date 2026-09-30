---
type: "Malware"
source: MITRE ATT&CK
id: "S9034"
source_url: "https://attack.mitre.org/software/S9034"
created: "2026-04-20"
modified: "2026-05-12"
---
# S9034: Tsundere Botnet

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9034  
**Platforms:** Linux, macOS, Windows  
**Tactics:** Not specified

## Source description

[Tsundere Botnet](https://attack.mitre.org/software/S9034) is a botnet first reported in mid-2025 that is delivered via MSI installer or a PowerShell script. It leverages Node.js and JavaScript for payload delivery and execution, and uses smart contracts on the blockchain to host command and control (C2) addresses. [Tsundere Botnet](https://attack.mitre.org/software/S9034) is attributed to a likely Russian-speaking threat actor. A variant named DinDoor has been linked to [MuddyWater](https://attack.mitre.org/groups/G0069) operations and uses the Deno runtime for execution rather than Node.js.(Citation: Checkpoint_MOISCyberCrime_Mar2026)(Citation: SOCRadar_MuddyWaterDindoor_Mar2026)(Citation: CAL_MuddyWater_Mar2026)(Citation: SecureListUbiedo_Tsundere_Nov2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9034](https://attack.mitre.org/software/S9034)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
