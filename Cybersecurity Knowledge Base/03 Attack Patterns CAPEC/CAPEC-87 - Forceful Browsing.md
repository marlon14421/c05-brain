---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-87"
status: "Draft"
---
# CAPEC-87: Forceful Browsing

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An attacker employs forceful browsing (direct URL entry) to access portions of a website that are otherwise unreachable. Usually, a front controller or similar design pattern is employed to protect access to portions of a web application. Forceful browsing enables an attacker to access information, perform privileged operations and otherwise reach sections of the web application that have been improperly protected.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-87 on capec.mitre.org](https://capec.mitre.org/data/definitions/87.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
