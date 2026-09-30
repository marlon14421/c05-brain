---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-197"
status: "Draft"
---
# CAPEC-197: Exponential Data Expansion

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** High

## Description

An adversary submits data to a target application which contains nested exponential data expansion to produce excessively large output. Many data format languages allow the definition of macro-like structures that can be used to simplify the creation of complex structures. However, this capability can be abused to create excessive demands on a processor's CPU and memory. A small number of nested expansions can result in an exponential growth in demands on memory.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-197 on capec.mitre.org](https://capec.mitre.org/data/definitions/197.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
