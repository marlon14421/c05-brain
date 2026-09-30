---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-227"
status: "Draft"
---
# CAPEC-227: Sustained Client Engagement

**Abstraction:** Meta  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary attempts to deny legitimate users access to a resource by continually engaging a specific resource in an attempt to keep the resource tied up as long as possible. The adversary's primary goal is not to crash or flood the target, which would alert defenders; rather it is to repeatedly perform actions or abuse algorithmic flaws such that a given resource is tied up and not available to a legitimate user. By carefully crafting a requests that keep the resource engaged through what is seemingly benign requests, legitimate users are limited or completely denied access to the resource.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-227 on capec.mitre.org](https://capec.mitre.org/data/definitions/227.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
