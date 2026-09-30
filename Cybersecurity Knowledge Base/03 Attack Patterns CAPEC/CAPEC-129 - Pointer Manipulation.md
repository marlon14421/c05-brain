---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-129"
status: "Draft"
---
# CAPEC-129: Pointer Manipulation

**Abstraction:** Meta  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

This attack pattern involves an adversary manipulating a pointer within a target application resulting in the application accessing an unintended memory location. This can result in the crashing of the application or, for certain pointer values, access to data that would not normally be possible or the execution of arbitrary code. Since pointers are simply integer variables, Integer Attacks may often be used in Pointer Attacks.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-129 on capec.mitre.org](https://capec.mitre.org/data/definitions/129.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
