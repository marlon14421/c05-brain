---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-576"
status: "Stable"
---
# CAPEC-576: Group Permission Footprinting

**Abstraction:** Standard  
**Catalog severity:** Low  
**Catalog likelihood:** Low

## Description

An adversary exploits functionality meant to identify information about user groups and their permissions on the target system to an authorized user. By knowing what users/permissions are registered on the target system, the adversary can inform further and more targeted malicious behavior. An example Windows command which can list local groups is "net localgroup".

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-576 on capec.mitre.org](https://capec.mitre.org/data/definitions/576.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
