---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-568"
status: "Draft"
---
# CAPEC-568: Capture Credentials via Keylogger

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Not stated

## Description

An adversary deploys a keylogger in an effort to obtain credentials directly from a system's user. After capturing all the keystrokes made by a user, the adversary can analyze the data and determine which string are likely to be passwords or other credential related information.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-568 on capec.mitre.org](https://capec.mitre.org/data/definitions/568.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
