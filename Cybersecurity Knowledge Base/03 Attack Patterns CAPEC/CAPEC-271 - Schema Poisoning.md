---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-271"
status: "Draft"
---
# CAPEC-271: Schema Poisoning

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An adversary corrupts or modifies the content of a schema for the purpose of undermining the security of the target. Schemas provide the structure and content definitions for resources used by an application. By replacing or modifying a schema, the adversary can affect how the application handles or interprets a resource, often leading to possible denial of service, entering into an unexpected state, or recording incomplete data.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-271 on capec.mitre.org](https://capec.mitre.org/data/definitions/271.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
