---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-201"
status: "Draft"
---
# CAPEC-201: Serialized Data External Linking

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An adversary creates a serialized data file (e.g. XML, YAML, etc...) that contains an external data reference. Because serialized data parsers may not validate documents with external references, there may be no checks on the nature of the reference in the external data. This can allow an adversary to open arbitrary files or connections, which may further lead to the adversary gaining access to information on the system that they would normally be unable to obtain.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-201 on capec.mitre.org](https://capec.mitre.org/data/definitions/201.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
