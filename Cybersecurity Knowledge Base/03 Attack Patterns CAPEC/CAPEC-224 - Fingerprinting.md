---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-224"
status: "Stable"
---
# CAPEC-224: Fingerprinting

**Abstraction:** Meta  
**Catalog severity:** Very Low  
**Catalog likelihood:** High

## Description

An adversary compares output from a target system to known indicators that uniquely identify specific details about the target. Most commonly, fingerprinting is done to determine operating system and application versions. Fingerprinting can be done passively as well as actively. Fingerprinting by itself is not usually detrimental to the target. However, the information gathered through fingerprinting often enables an adversary to discover existing weaknesses in the target.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-224 on capec.mitre.org](https://capec.mitre.org/data/definitions/224.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
