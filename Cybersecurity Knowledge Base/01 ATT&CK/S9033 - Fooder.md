---
type: "Malware"
source: MITRE ATT&CK
id: "S9033"
source_url: "https://attack.mitre.org/software/S9033"
created: "2026-04-20"
modified: "2026-04-23"
---
# S9033: Fooder

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9033  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Fooder](https://attack.mitre.org/software/S9033) is a custom 64-bit C/C++ loader used by [MuddyWater](https://attack.mitre.org/groups/G0069) that can decrypt and reflectively load embedded payloads such as a go-socks5 proxy utility, the open-source HackBrowserData infostealer, or the [MuddyViper](https://attack.mitre.org/software/S9032) backdoor. [Fooder](https://attack.mitre.org/software/S9033) has frequently masqueraded as an entertainment executable, such as the Snake game (e.g., `Snake_Game.exe`).(Citation: ESET_MuddyWater_Dec2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9033](https://attack.mitre.org/software/S9033)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
