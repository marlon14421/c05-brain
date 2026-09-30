---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-657"
status: "Draft"
---
# CAPEC-657: Malicious Automated Software Update via Spoofing

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An attackers uses identify or content spoofing to trick a client into performing an automated software update from a malicious source. A malicious automated software update that leverages spoofing can include content or identity spoofing as well as protocol spoofing. Content or identity spoofing attacks can trigger updates in software by embedding scripted mechanisms within a malicious web page, which masquerades as a legitimate update source. Scripting mechanisms communicate with software components and trigger updates from locations specified by the attackers' server. The result is the client believing there is a legitimate software update available but instead downloading a malicious update from the attacker.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-657 on capec.mitre.org](https://capec.mitre.org/data/definitions/657.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
