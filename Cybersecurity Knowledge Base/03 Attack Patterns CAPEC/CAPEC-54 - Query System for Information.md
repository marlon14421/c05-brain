---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-54"
status: "Draft"
---
# CAPEC-54: Query System for Information

**Abstraction:** Standard  
**Catalog severity:** Low  
**Catalog likelihood:** High

## Description

An adversary, aware of an application's location (and possibly authorized to use the application), probes an application's structure and evaluates its robustness by submitting requests and examining responses. Often, this is accomplished by sending variants of expected queries in the hope that these modified queries might return information beyond what the expected set of queries would provide.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-54 on capec.mitre.org](https://capec.mitre.org/data/definitions/54.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
