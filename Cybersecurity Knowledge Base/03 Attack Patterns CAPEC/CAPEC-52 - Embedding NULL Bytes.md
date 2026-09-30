---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-52"
status: "Draft"
---
# CAPEC-52: Embedding NULL Bytes

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An adversary embeds one or more null bytes in input to the target software. This attack relies on the usage of a null-valued byte as a string terminator in many environments. The goal is for certain components of the target software to stop processing the input when it encounters the null byte(s).

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-52 on capec.mitre.org](https://capec.mitre.org/data/definitions/52.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
