---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-278"
status: "Draft"
---
# CAPEC-278: Web Services Protocol Manipulation

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary manipulates a web service related protocol to cause a web application or service to react differently than intended. This can either be performed through the manipulation of call parameters to include unexpected values, or by changing the called function to one that should normally be restricted or limited. By leveraging this pattern of attack, the adversary is able to gain access to data or resources normally restricted, or to cause the application or service to crash.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-278 on capec.mitre.org](https://capec.mitre.org/data/definitions/278.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
