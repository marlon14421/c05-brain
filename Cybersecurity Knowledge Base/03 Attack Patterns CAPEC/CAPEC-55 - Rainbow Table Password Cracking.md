---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-55"
status: "Draft"
---
# CAPEC-55: Rainbow Table Password Cracking

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Medium

## Description

An attacker gets access to the database table where hashes of passwords are stored. They then use a rainbow table of pre-computed hash chains to attempt to look up the original password. Once the original password corresponding to the hash is obtained, the attacker uses the original password to gain access to the system.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-55 on capec.mitre.org](https://capec.mitre.org/data/definitions/55.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
