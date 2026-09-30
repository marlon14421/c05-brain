---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-485"
status: "Draft"
---
# CAPEC-485: Signature Spoofing by Key Recreation

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An attacker obtains an authoritative or reputable signer's private signature key by exploiting a cryptographic weakness in the signature algorithm or pseudorandom number generation and then uses this key to forge signatures from the original signer to mislead a victim into performing actions that benefit the attacker.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-485 on capec.mitre.org](https://capec.mitre.org/data/definitions/485.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
