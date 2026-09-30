---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-480"
status: "Draft"
---
# CAPEC-480: Escaping Virtualization

**Abstraction:** Standard  
**Catalog severity:** Very High  
**Catalog likelihood:** Low

## Description

An adversary gains access to an application, service, or device with the privileges of an authorized or privileged user by escaping the confines of a virtualized environment. The adversary is then able to access resources or execute unauthorized code within the host environment, generally with the privileges of the user running the virtualized process. Successfully executing an attack of this type is often the first step in executing more complex attacks.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-480 on capec.mitre.org](https://capec.mitre.org/data/definitions/480.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
