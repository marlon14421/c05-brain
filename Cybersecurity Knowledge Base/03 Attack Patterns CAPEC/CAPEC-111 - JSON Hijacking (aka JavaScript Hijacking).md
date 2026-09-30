---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-111"
status: "Draft"
---
# CAPEC-111: JSON Hijacking (aka JavaScript Hijacking)

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An attacker targets a system that uses JavaScript Object Notation (JSON) as a transport mechanism between the client and the server (common in Web 2.0 systems using AJAX) to steal possibly confidential information transmitted from the server back to the client inside the JSON object by taking advantage of the loophole in the browser's Same Origin Policy that does not prohibit JavaScript from one website to be included and executed in the context of another website.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-111 on capec.mitre.org](https://capec.mitre.org/data/definitions/111.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
