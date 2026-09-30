---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-649"
status: "Draft"
---
# CAPEC-649: Adding a Space to a File Extension

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Low

## Description

An adversary adds a space character to the end of a file extension and takes advantage of an application that does not properly neutralize trailing special elements in file names. This extra space, which can be difficult for a user to notice, affects which default application is used to operate on the file and can be leveraged by the adversary to control execution.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-649 on capec.mitre.org](https://capec.mitre.org/data/definitions/649.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
