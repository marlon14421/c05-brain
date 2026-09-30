---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-76"
status: "Draft"
---
# CAPEC-76: Manipulating Web Input to File System Calls

**Abstraction:** Detailed  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

An attacker manipulates inputs to the target software which the target software passes to file system calls in the OS. The goal is to gain access to, and perhaps modify, areas of the file system that the target software did not intend to be accessible.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-76 on capec.mitre.org](https://capec.mitre.org/data/definitions/76.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
