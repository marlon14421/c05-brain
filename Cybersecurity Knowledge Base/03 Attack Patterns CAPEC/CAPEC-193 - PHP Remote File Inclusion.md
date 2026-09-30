---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-193"
status: "Draft"
---
# CAPEC-193: PHP Remote File Inclusion

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

In this pattern the adversary is able to load and execute arbitrary code remotely available from the application. This is usually accomplished through an insecurely configured PHP runtime environment and an improperly sanitized "include" or "require" call, which the user can then control to point to any web-accessible file. This allows adversaries to hijack the targeted application and force it to execute their own instructions.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-193 on capec.mitre.org](https://capec.mitre.org/data/definitions/193.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
