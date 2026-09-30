---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-595"
status: "Draft"
---
# CAPEC-595: Connection Reset

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

In this attack pattern, an adversary injects a connection reset packet to one or both ends of a target's connection. The attacker is therefore able to have the target and/or the destination server sever the connection without having to directly filter the traffic between them.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-595 on capec.mitre.org](https://capec.mitre.org/data/definitions/595.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
