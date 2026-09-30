---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-146"
status: "Stable"
---
# CAPEC-146: XML Schema Poisoning

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An adversary corrupts or modifies the content of XML schema information passed between a client and server for the purpose of undermining the security of the target. XML Schemas provide the structure and content definitions for XML documents. Schema poisoning is the ability to manipulate a schema either by replacing or modifying it to compromise the programs that process documents that use this schema.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-146 on capec.mitre.org](https://capec.mitre.org/data/definitions/146.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
