---
type: "Malware"
source: MITRE ATT&CK
id: "S1249"
source_url: "https://attack.mitre.org/software/S1249"
created: "2025-10-22"
modified: "2025-10-24"
---
# S1249: HexEval Loader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1249  
**Platforms:** Linux, macOS, Windows  
**Tactics:** Not specified

## Source description

[HexEval Loader](https://attack.mitre.org/software/S1249) is a hex-encoded loader that collects host data, decodes follow-on scripts and acts as a downloader for the [BeaverTail](https://attack.mitre.org/software/S1246) malware. [HexEval Loader](https://attack.mitre.org/software/S1249) was first reported in April 2025. [HexEval Loader](https://attack.mitre.org/software/S1249) has previously been leveraged by North Korea-affiliated threat actors identified as [Contagious Interview](https://attack.mitre.org/groups/G1052). [HexEval Loader](https://attack.mitre.org/software/S1249) has been delivered to victims through code repository sites utilizing typosquatting naming conventions of various npm packages.(Citation: Socket Contagious Interview NPM April 2025)(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)(Citation: Socket HexEval BeaverTail Contagious Interview June 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1249](https://attack.mitre.org/software/S1249)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
