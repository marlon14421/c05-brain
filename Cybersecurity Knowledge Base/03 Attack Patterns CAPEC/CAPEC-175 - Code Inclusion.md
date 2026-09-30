---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-175"
status: "Stable"
---
# CAPEC-175: Code Inclusion

**Abstraction:** Meta  
**Catalog severity:** Very High  
**Catalog likelihood:** Medium

## Description

An adversary exploits a weakness on the target to force arbitrary code to be retrieved locally or from a remote location and executed. This differs from code injection in that code injection involves the direct inclusion of code while code inclusion involves the addition or replacement of a reference to a code file, which is subsequently loaded by the target and used as part of the code of some application.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-175 on capec.mitre.org](https://capec.mitre.org/data/definitions/175.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
