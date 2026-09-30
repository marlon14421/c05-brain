---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-313"
status: "Stable"
---
# CAPEC-313: Passive OS Fingerprinting

**Abstraction:** Standard  
**Catalog severity:** Low  
**Catalog likelihood:** High

## Description

An adversary engages in activity to detect the version or type of OS software in a an environment by passively monitoring communication between devices, nodes, or applications. Passive techniques for operating system detection send no actual probes to a target, but monitor network or client-server communication between nodes in order to identify operating systems based on observed behavior as compared to a database of known signatures or values. While passive OS fingerprinting is not usually as reliable as active methods, it is generally better able to evade detection.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-313 on capec.mitre.org](https://capec.mitre.org/data/definitions/313.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
