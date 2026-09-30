---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-29"
status: "Draft"
---
# CAPEC-29: Leveraging Time-of-Check and Time-of-Use (TOCTOU) Race Conditions

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This attack targets a race condition occurring between the time of check (state) for a resource and the time of use of a resource. A typical example is file access. The adversary can leverage a file access race condition by "running the race", meaning that they would modify the resource between the first time the target program accesses the file and the time the target program uses the file. During that period of time, the adversary could replace or modify the file, causing the application to behave unexpectedly.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-29 on capec.mitre.org](https://capec.mitre.org/data/definitions/29.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
