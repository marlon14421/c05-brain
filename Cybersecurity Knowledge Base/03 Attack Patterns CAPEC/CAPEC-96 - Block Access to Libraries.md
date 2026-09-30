---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-96"
status: "Draft"
---
# CAPEC-96: Block Access to Libraries

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Medium

## Description

An application typically makes calls to functions that are a part of libraries external to the application. These libraries may be part of the operating system or they may be third party libraries. It is possible that the application does not handle situations properly where access to these libraries has been blocked. Depending on the error handling within the application, blocked access to libraries may leave the system in an insecure state that could be leveraged by an attacker.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-96 on capec.mitre.org](https://capec.mitre.org/data/definitions/96.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
