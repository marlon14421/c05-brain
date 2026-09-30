---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-392"
status: "Draft"
---
# CAPEC-392: Lock Bumping

**Abstraction:** Detailed  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An attacker uses a bump key to force a lock on a building or facility and gain entry. Lock Bumping is the use of a special type of key that can be tapped or bumped to cause the pins within the lock to fall into temporary alignment, allowing the lock to be opened. Lock bumping allows an attacker to open a lock without having the correct key. A standard lock is secured by a set of internal pins that prevent the device from turning. Spring loaded driver pins push down on the key pins. When the correct key is inserted, the ridges on the key push the key pins up and against the driver pins, causing correct alignment which allows the lock cylinder to rotate. A bump key is a specially constructed key that exploits this design. When the bump key is struck or firmly tapped, its teeth transfer the force of the tap into the key pins, causing the lock to momentarily shift into proper alignment for the mechanism to be opened.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-392 on capec.mitre.org](https://capec.mitre.org/data/definitions/392.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
