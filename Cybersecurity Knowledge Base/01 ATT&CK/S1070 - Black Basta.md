---
type: "Malware"
source: MITRE ATT&CK
id: "S1070"
source_url: "https://attack.mitre.org/software/S1070"
created: "2023-03-08"
modified: "2025-10-21"
---
# S1070: Black Basta

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1070  
**Platforms:** Windows, ESXi  
**Tactics:** Not specified

## Source description

[Black Basta](https://attack.mitre.org/software/S1070) is ransomware written in C++ that has been offered within the ransomware-as-a-service (RaaS) model since at least April 2022; there are variants that target Windows and VMWare ESXi servers. [Black Basta](https://attack.mitre.org/software/S1070) operations have included the double extortion technique where in addition to demanding ransom for decrypting the files of targeted organizations the cyber actors also threaten to post sensitive information to a leak site if the ransom is not paid. [Black Basta](https://attack.mitre.org/software/S1070) affiliates have targeted multiple high-value organizations, with the largest number of victims based in the U.S. Based on similarities in TTPs, leak sites, payment sites, and negotiation tactics, security researchers assess the [Black Basta](https://attack.mitre.org/software/S1070) RaaS operators could include current or former members of the [Conti](https://attack.mitre.org/software/S0575) group.(Citation: Palo Alto Networks Black Basta August 2022)(Citation: Deep Instinct Black Basta August 2022)(Citation: Minerva Labs Black Basta May 2022)(Citation: Avertium Black Basta June 2022)(Citation: NCC Group Black Basta June 2022)(Citation: Cyble Black Basta May 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1070](https://attack.mitre.org/software/S1070)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
