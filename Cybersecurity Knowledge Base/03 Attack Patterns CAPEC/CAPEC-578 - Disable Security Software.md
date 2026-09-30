---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-578"
status: "Usable"
---
# CAPEC-578: Disable Security Software

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** Medium

## Description

An adversary exploits a weakness in access control to disable security tools so that detection does not occur. This can take the form of killing processes, deleting registry keys so that tools do not start at run time, deleting log files, or other methods.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-578 on capec.mitre.org](https://capec.mitre.org/data/definitions/578.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
