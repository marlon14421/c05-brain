---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-68"
status: "Draft"
---
# CAPEC-68: Subvert Code-signing Facilities

**Abstraction:** Standard  
**Catalog severity:** Very High  
**Catalog likelihood:** Low

## Description

Many languages use code signing facilities to vouch for code's identity and to thus tie code to its assigned privileges within an environment. Subverting this mechanism can be instrumental in an attacker escalating privilege. Any means of subverting the way that a virtual machine enforces code signing classifies for this style of attack.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-68 on capec.mitre.org](https://capec.mitre.org/data/definitions/68.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
