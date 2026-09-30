---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-25"
status: "Stable"
---
# CAPEC-25: Forced Deadlock

**Abstraction:** Meta  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

The adversary triggers and exploits a deadlock condition in the target software to cause a denial of service. A deadlock can occur when two or more competing actions are waiting for each other to finish, and thus neither ever does. Deadlock conditions can be difficult to detect.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-25 on capec.mitre.org](https://capec.mitre.org/data/definitions/25.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
