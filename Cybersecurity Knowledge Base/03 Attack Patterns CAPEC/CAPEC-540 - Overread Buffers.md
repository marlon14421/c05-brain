---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-540"
status: "Draft"
---
# CAPEC-540: Overread Buffers

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An adversary attacks a target by providing input that causes an application to read beyond the boundary of a defined buffer. This typically occurs when a value influencing where to start or stop reading is set to reflect positions outside of the valid memory location of the buffer. This type of attack may result in exposure of sensitive information, a system crash, or arbitrary code execution.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-540 on capec.mitre.org](https://capec.mitre.org/data/definitions/540.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
