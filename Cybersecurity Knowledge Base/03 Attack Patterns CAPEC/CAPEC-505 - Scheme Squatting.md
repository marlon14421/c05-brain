---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-505"
status: "Draft"
---
# CAPEC-505: Scheme Squatting

**Abstraction:** Detailed  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary, through a previously installed malicious application, registers for a URL scheme intended for a target application that has not been installed. Thereafter, messages intended for the target application are handled by the malicious application. Upon receiving a message, the malicious application displays a screen that mimics the target application, thereby convincing the user to enter sensitive information. This type of attack is most often used to obtain sensitive information (e.g., credentials) from the user as they think that they are interacting with the intended target application.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-505 on capec.mitre.org](https://capec.mitre.org/data/definitions/505.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
