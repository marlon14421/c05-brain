---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-635"
status: "Draft"
---
# CAPEC-635: Alternative Execution Due to Deceptive Filenames

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Not stated

## Description

The extension of a file name is often used in various contexts to determine the application that is used to open and use it. If an attacker can cause an alternative application to be used, it may be able to execute malicious code, cause a denial of service or expose sensitive information.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-635 on capec.mitre.org](https://capec.mitre.org/data/definitions/635.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
