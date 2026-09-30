---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-78"
status: "Draft"
---
# CAPEC-78: Using Escaped Slashes in Alternate Encoding

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This attack targets the use of the backslash in alternate encoding. An adversary can provide a backslash as a leading character and causes a parser to believe that the next character is special. This is called an escape. By using that trick, the adversary tries to exploit alternate ways to encode the same character which leads to filter problems and opens avenues to attack.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-78 on capec.mitre.org](https://capec.mitre.org/data/definitions/78.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
