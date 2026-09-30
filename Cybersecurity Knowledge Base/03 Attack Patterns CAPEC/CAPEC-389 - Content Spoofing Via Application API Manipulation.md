---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-389"
status: "Draft"
---
# CAPEC-389: Content Spoofing Via Application API Manipulation

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An attacker manipulates either egress or ingress data from a client within an application framework in order to change the content of messages. Performing this attack allows the attacker to manipulate content in such a way as to produce messages or content that look authentic but may contain deceptive links, spam-like content, or links to the attackers' code. In general, content-spoofing within an application API can be employed to stage many different types of attacks varied based on the attackers' intent. The techniques require use of specialized software that allow the attacker to use adversary-in-the-middle (CAPEC-94) communications between the web browser and the remote system.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-389 on capec.mitre.org](https://capec.mitre.org/data/definitions/389.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
