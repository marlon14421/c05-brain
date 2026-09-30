---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-625"
status: "Draft"
---
# CAPEC-625: Mobile Device Fault Injection

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

Fault injection attacks against mobile devices use disruptive signals or events (e.g. electromagnetic pulses, laser pulses, clock glitches, etc.) to cause faulty behavior. When performed in a controlled manner on devices performing cryptographic operations, this faulty behavior can be exploited to derive secret key information. Although this attack usually requires physical control of the mobile device, it is non-destructive, and the device can be used after the attack without any indication that secret keys were compromised.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-625 on capec.mitre.org](https://capec.mitre.org/data/definitions/625.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
