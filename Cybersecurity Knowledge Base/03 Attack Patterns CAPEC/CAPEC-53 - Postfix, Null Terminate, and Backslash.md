---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-53"
status: "Draft"
---
# CAPEC-53: Postfix, Null Terminate, and Backslash

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

If a string is passed through a filter of some kind, then a terminal NULL may not be valid. Using alternate representation of NULL allows an adversary to embed the NULL mid-string while postfixing the proper data so that the filter is avoided. One example is a filter that looks for a trailing slash character. If a string insertion is possible, but the slash must exist, an alternate encoding of NULL in mid-string may be used.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-53 on capec.mitre.org](https://capec.mitre.org/data/definitions/53.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
