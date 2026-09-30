---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-3"
status: "Draft"
---
# CAPEC-3: Using Leading 'Ghost' Character Sequences to Bypass Input Filters

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Medium

## Description

Some APIs will strip certain leading characters from a string of parameters. An adversary can intentionally introduce leading "ghost" characters (extra characters that don't affect the validity of the request at the API layer) that enable the input to pass the filters and therefore process the adversary's input. This occurs when the targeted API will accept input data in several syntactic forms and interpret it in the equivalent semantic way, while the filter does not take into account the full spectrum of the syntactic forms acceptable to the targeted API.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-3 on capec.mitre.org](https://capec.mitre.org/data/definitions/3.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
