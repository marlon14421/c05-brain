---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-46"
status: "Draft"
---
# CAPEC-46: Overflow Variables and Tags

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This type of attack leverages the use of tags or variables from a formatted configuration data to cause buffer overflow. The adversary crafts a malicious HTML page or configuration file that includes oversized strings, thus causing an overflow.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-46 on capec.mitre.org](https://capec.mitre.org/data/definitions/46.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
