---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-49"
status: "Draft"
---
# CAPEC-49: Password Brute Forcing

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

An adversary tries every possible value for a password until they succeed. A brute force attack, if feasible computationally, will always be successful because it will essentially go through all possible passwords given the alphabet used (lower case letters, upper case letters, numbers, symbols, etc.) and the maximum length of the password.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-49 on capec.mitre.org](https://capec.mitre.org/data/definitions/49.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
