---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-40"
status: "Draft"
---
# CAPEC-40: Manipulating Writeable Terminal Devices

**Abstraction:** Standard  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

This attack exploits terminal devices that allow themselves to be written to by other users. The attacker sends command strings to the target terminal device hoping that the target user will hit enter and thereby execute the malicious command with their privileges. The attacker can send the results (such as copying /etc/passwd) to a known directory and collect once the attack has succeeded.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-40 on capec.mitre.org](https://capec.mitre.org/data/definitions/40.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
