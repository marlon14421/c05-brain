---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-499"
status: "Draft"
---
# CAPEC-499: Android Intent Intercept

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary, through a previously installed malicious application, intercepts messages from a trusted Android-based application in an attempt to achieve a variety of different objectives including denial of service, information disclosure, and data injection. An implicit intent sent from a trusted application can be received by any application that has declared an appropriate intent filter. If the intent is not protected by a permission that the malicious application lacks, then the attacker can gain access to the data contained within the intent. Further, the intent can be either blocked from reaching the intended destination, or modified and potentially forwarded along.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-499 on capec.mitre.org](https://capec.mitre.org/data/definitions/499.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
