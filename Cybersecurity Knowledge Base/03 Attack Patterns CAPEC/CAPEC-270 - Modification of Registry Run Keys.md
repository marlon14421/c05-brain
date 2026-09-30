---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-270"
status: "Stable"
---
# CAPEC-270: Modification of Registry Run Keys

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Medium

## Description

An adversary adds a new entry to the "run keys" in the Windows registry so that an application of their choosing is executed when a user logs in. In this way, the adversary can get their executable to operate and run on the target system with the authorized user's level of permissions. This attack is a good way for an adversary to run persistent spyware on a user's machine, such as a keylogger.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-270 on capec.mitre.org](https://capec.mitre.org/data/definitions/270.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
