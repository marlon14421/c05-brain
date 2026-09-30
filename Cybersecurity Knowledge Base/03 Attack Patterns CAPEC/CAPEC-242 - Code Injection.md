---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-242"
status: "Stable"
---
# CAPEC-242: Code Injection

**Abstraction:** Meta  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An adversary exploits a weakness in input validation on the target to inject new code into that which is currently executing. This differs from code inclusion in that code inclusion involves the addition or replacement of a reference to a code file, which is subsequently loaded by the target and used as part of the code of some application.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-242 on capec.mitre.org](https://capec.mitre.org/data/definitions/242.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
