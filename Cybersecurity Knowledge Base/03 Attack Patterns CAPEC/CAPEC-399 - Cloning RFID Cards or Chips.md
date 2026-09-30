---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-399"
status: "Draft"
---
# CAPEC-399: Cloning RFID Cards or Chips

**Abstraction:** Detailed  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An attacker analyzes data returned by an RFID chip and uses this information to duplicate a RFID signal that responds identically to the target chip. In some cases RFID chips are used for building access control, employee identification, or as markers on products being delivered along a supply chain. Some organizations also embed RFID tags inside computer assets to trigger alarms if they are removed from particular rooms, zones, or buildings. Similar to Magnetic strip cards, RFID cards are susceptible to duplication (cloning) and reuse.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-399 on capec.mitre.org](https://capec.mitre.org/data/definitions/399.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
