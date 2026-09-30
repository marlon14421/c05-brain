---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-17"
status: "Draft"
---
# CAPEC-17: Using Malicious Files

**Abstraction:** Standard  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

An attack of this type exploits a system's configuration that allows an adversary to either directly access an executable file, for example through shell access; or in a possible worst case allows an adversary to upload a file and then execute it. Web servers, ftp servers, and message oriented middleware systems which have many integration points are particularly vulnerable, because both the programmers and the administrators must be in synch regarding the interfaces and the correct privileges for each interface.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-17 on capec.mitre.org](https://capec.mitre.org/data/definitions/17.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
