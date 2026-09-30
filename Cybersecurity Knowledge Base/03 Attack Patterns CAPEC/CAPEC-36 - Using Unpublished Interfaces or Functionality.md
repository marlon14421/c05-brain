---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-36"
status: "Draft"
---
# CAPEC-36: Using Unpublished Interfaces or Functionality

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

An adversary searches for and invokes interfaces or functionality that the target system designers did not intend to be publicly available. If interfaces fail to authenticate requests, the attacker may be able to invoke functionality they are not authorized for.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-36 on capec.mitre.org](https://capec.mitre.org/data/definitions/36.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
