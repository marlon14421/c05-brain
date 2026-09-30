---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-636"
status: "Draft"
---
# CAPEC-636: Hiding Malicious Data or Code within Files

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Not stated

## Description

Files on various operating systems can have a complex format which allows for the storage of other data, in addition to its contents. Often this is metadata about the file, such as a cached thumbnail for an image file. Unless utilities are invoked in a particular way, this data is not visible during the normal use of the file. It is possible for an attacker to store malicious data or code using these facilities, which would be difficult to discover.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-636 on capec.mitre.org](https://capec.mitre.org/data/definitions/636.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
