---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-251"
status: "Stable"
---
# CAPEC-251: Local Code Inclusion

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

The attacker forces an application to load arbitrary code files from the local machine. The attacker could use this to try to load old versions of library files that have known vulnerabilities, to load files that the attacker placed on the local machine during a prior attack, or to otherwise change the functionality of the targeted application in unexpected ways.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-251 on capec.mitre.org](https://capec.mitre.org/data/definitions/251.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
