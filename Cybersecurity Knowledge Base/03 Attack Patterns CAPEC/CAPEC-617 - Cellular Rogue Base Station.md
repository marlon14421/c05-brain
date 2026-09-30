---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-617"
status: "Draft"
---
# CAPEC-617: Cellular Rogue Base Station

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

In this attack scenario, the attacker imitates a cellular base station with their own "rogue" base station equipment. Since cellular devices connect to whatever station has the strongest signal, the attacker can easily convince a targeted cellular device (e.g. the retransmission device) to talk to the rogue base station.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-617 on capec.mitre.org](https://capec.mitre.org/data/definitions/617.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
