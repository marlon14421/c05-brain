---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-461"
status: "Draft"
---
# CAPEC-461: Web Services API Signature Forgery Leveraging Hash Function Extension Weakness

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Not stated

## Description

An adversary utilizes a hash function extension/padding weakness, to modify the parameters passed to the web service requesting authentication by generating their own call in order to generate a legitimate signature hash (as described in the notes), without knowledge of the secret token sometimes provided by the web service.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-461 on capec.mitre.org](https://capec.mitre.org/data/definitions/461.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
