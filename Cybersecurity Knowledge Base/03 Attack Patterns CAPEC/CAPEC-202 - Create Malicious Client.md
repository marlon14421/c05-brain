---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-202"
status: "Draft"
---
# CAPEC-202: Create Malicious Client

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

An adversary creates a client application to interface with a target service where the client violates assumptions the service makes about clients. Services that have designated client applications (as opposed to services that use general client applications, such as IMAP or POP mail servers which can interact with any IMAP or POP client) may assume that the client will follow specific procedures.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-202 on capec.mitre.org](https://capec.mitre.org/data/definitions/202.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
