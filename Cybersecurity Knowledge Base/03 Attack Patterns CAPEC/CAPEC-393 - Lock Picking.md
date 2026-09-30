---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-393"
status: "Draft"
---
# CAPEC-393: Lock Picking

**Abstraction:** Detailed  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An attacker uses lock picking tools and techniques to bypass the locks on a building or facility. Lock picking is the use of a special set of tools to manipulate the pins within a lock. Different sets of tools are required for each type of lock. Lock picking attacks have the advantage of being non-invasive in that if performed correctly the lock will not be damaged. A standard lock pin-and-tumbler lock is secured by a set of internal pins that prevent the tumbler device from turning. Spring loaded driver pins push down on the key pins preventing rotation so that the bolt remains in a locked position.. When the correct key is inserted, the ridges on the key push the key pins up and against the driver pins, causing correct alignment which allows the lock cylinder to rotate. Most common locks, such as domestic locks in the US, can be picked using a standard 2 tools (i.e. a torsion wrench and a hook pick).

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-393 on capec.mitre.org](https://capec.mitre.org/data/definitions/393.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
