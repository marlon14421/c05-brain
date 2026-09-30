---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-394"
status: "Draft"
---
# CAPEC-394: Using a Snap Gun Lock to Force a Lock

**Abstraction:** Detailed  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An attacker uses a Snap Gun, also known as a Pick Gun, to force the lock on a building or facility. A Pick Gun is a special type of lock picking instrument that works on similar principles as lock bumping. A snap gun is a hand-held device with an attached metal pick. The metal pick strikes the pins within the lock, transferring motion from the key pins to the driver pins and forcing the lock into momentary alignment. A standard lock is secured by a set of internal pins that prevent the device from turning. Spring loaded driver pins push down on the key pins. When the correct key is inserted, the ridges on the key push the key pins up and against the driver pins, causing correct alignment which allows the lock cylinder to rotate. A Snap Gun exploits this design by using a metal pin to strike all of the key pins at once, forcing the driver pins to shift into an unlocked position. Unlike bump keys or lock picks, a Snap Gun may damage the lock more easily, leaving evidence that the lock has been tampered with.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-394 on capec.mitre.org](https://capec.mitre.org/data/definitions/394.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
