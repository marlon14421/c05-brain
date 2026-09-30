---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-215"
status: "Draft"
---
# CAPEC-215: Fuzzing for application mapping

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** High

## Description

An attacker sends random, malformed, or otherwise unexpected messages to a target application and observes the application's log or error messages returned. The attacker does not initially know how a target will respond to individual messages but by attempting a large number of message variants they may find a variant that trigger's desired behavior. In this attack, the purpose of the fuzzing is to observe the application's log and error messages, although fuzzing a target can also sometimes cause the target to enter an unstable state, causing a crash.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-215 on capec.mitre.org](https://capec.mitre.org/data/definitions/215.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
