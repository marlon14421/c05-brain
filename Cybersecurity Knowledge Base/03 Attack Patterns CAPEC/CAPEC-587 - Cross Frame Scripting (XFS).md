---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-587"
status: "Draft"
---
# CAPEC-587: Cross Frame Scripting (XFS)

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Not stated

## Description

This attack pattern combines malicious Javascript and a legitimate webpage loaded into a concealed iframe. The malicious Javascript is then able to interact with a legitimate webpage in a manner that is unknown to the user. This attack usually leverages some element of social engineering in that an attacker must convinces a user to visit a web page that the attacker controls.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-587 on capec.mitre.org](https://capec.mitre.org/data/definitions/587.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
