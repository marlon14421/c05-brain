---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-248"
status: "Stable"
---
# CAPEC-248: Command Injection

**Abstraction:** Meta  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

An adversary looking to execute a command of their choosing, injects new items into an existing command thus modifying interpretation away from what was intended. Commands in this context are often standalone strings that are interpreted by a downstream component and cause specific responses. This type of attack is possible when untrusted values are used to build these command strings. Weaknesses in input validation or command construction can enable the attack and lead to successful exploitation.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-248 on capec.mitre.org](https://capec.mitre.org/data/definitions/248.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
