---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-582"
status: "Draft"
---
# CAPEC-582: Route Disabling

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An adversary disables the network route between two targets. The goal is to completely sever the communications channel between two entities. This is often the result of a major error or the use of an "Internet kill switch" by those in control of critical infrastructure. This attack pattern differs from most other obstruction patterns by targeting the route itself, as opposed to the data passed over the route.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-582 on capec.mitre.org](https://capec.mitre.org/data/definitions/582.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
