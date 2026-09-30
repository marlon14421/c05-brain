---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-26"
status: "Stable"
---
# CAPEC-26: Leveraging Race Conditions

**Abstraction:** Meta  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

The adversary targets a race condition occurring when multiple processes access and manipulate the same resource concurrently, and the outcome of the execution depends on the particular order in which the access takes place. The adversary can leverage a race condition by "running the race", modifying the resource and modifying the normal execution flow. For instance, a race condition can occur while accessing a file: the adversary can trick the system by replacing the original file with their version and cause the system to read the malicious file.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-26 on capec.mitre.org](https://capec.mitre.org/data/definitions/26.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
