---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-250"
status: "Draft"
---
# CAPEC-250: XML Injection

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** High

## Description

An attacker utilizes crafted XML user-controllable input to probe, attack, and inject data into the XML database, using techniques similar to SQL injection. The user-controllable input can allow for unauthorized viewing of data, bypassing authentication or the front-end application for direct XML database access, and possibly altering database information.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-250 on capec.mitre.org](https://capec.mitre.org/data/definitions/250.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
