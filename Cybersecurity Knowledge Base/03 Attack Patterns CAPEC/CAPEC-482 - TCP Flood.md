---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-482"
status: "Draft"
---
# CAPEC-482: TCP Flood

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary may execute a flooding attack using the TCP protocol with the intent to deny legitimate users access to a service. These attacks exploit the weakness within the TCP protocol where there is some state information for the connection the server needs to maintain. This often involves the use of TCP SYN messages.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-482 on capec.mitre.org](https://capec.mitre.org/data/definitions/482.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
