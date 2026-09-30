---
type: "Malware"
source: MITRE ATT&CK
id: "S9010"
source_url: "https://attack.mitre.org/software/S9010"
created: "2026-04-10"
modified: "2026-04-24"
---
# S9010: GlassWorm

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9010  
**Platforms:** macOS, Windows  
**Tactics:** Not specified

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) is a worm that propagated through supply chain attacks by compromising repository credentials from victim environments and having malicious payloads added to those compromised accounts for distribution to victims across the various development ecosystems.(Citation: Koi Glassworm InvisibleCode October 2025)(Citation: Aikido GlassWorm October 2025)(Citation: Socket GlassWorm January 2026) [GlassWorm](https://attack.mitre.org/software/S9010) has numerous variants, including Rust binaries, encrypted JavaScript and a variant leveraging invisible Unicode characters that made reverse engineering difficult.(Citation: Koi Glassworm New Tricks December 2025)(Citation: Koi Glassworm InvisibleCode October 2025)(Citation: Koi GlassWorm Rust December 2025) [GlassWorm](https://attack.mitre.org/software/S9010) has employed a unique command and control (C2) methodology using Solana blockchain.(Citation: Koi Glassworm Extensions November 2025)(Citation: Koi Glassworm InvisibleCode October 2025) [GlassWorm](https://attack.mitre.org/software/S9010) was first reported in October 2025.(Citation: Koi Glassworm Extensions November 2025)(Citation: Koi Glassworm InvisibleCode October 2025)(Citation: Socket GlassWorm January 2026)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9010](https://attack.mitre.org/software/S9010)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
