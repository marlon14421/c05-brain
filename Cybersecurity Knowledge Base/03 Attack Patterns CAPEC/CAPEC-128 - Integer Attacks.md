---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-128"
status: "Draft"
---
# CAPEC-128: Integer Attacks

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

An attacker takes advantage of the structure of integer variables to cause these variables to assume values that are not expected by an application. For example, adding one to the largest positive integer in a signed integer variable results in a negative number. Negative numbers may be illegal in an application and the application may prevent an attacker from providing them directly, but the application may not consider that adding two positive numbers can create a negative number do to the structure of integer storage formats.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-128 on capec.mitre.org](https://capec.mitre.org/data/definitions/128.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
