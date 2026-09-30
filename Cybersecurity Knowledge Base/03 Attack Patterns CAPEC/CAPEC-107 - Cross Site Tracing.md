---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-107"
status: "Draft"
---
# CAPEC-107: Cross Site Tracing

**Abstraction:** Detailed  
**Catalog severity:** Very High  
**Catalog likelihood:** Medium

## Description

Cross Site Tracing (XST) enables an adversary to steal the victim's session cookie and possibly other authentication credentials transmitted in the header of the HTTP request when the victim's browser communicates to a destination system's web server.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-107 on capec.mitre.org](https://capec.mitre.org/data/definitions/107.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
