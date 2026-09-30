---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-92"
status: "Draft"
---
# CAPEC-92: Forced Integer Overflow

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This attack forces an integer variable to go out of range. The integer variable is often used as an offset such as size of memory allocation or similarly. The attacker would typically control the value of such variable and try to get it out of range. For instance the integer in question is incremented past the maximum possible value, it may wrap to become a very small, or negative number, therefore providing a very incorrect value which can lead to unexpected behavior. At worst the attacker can execute arbitrary code.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-92 on capec.mitre.org](https://capec.mitre.org/data/definitions/92.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
