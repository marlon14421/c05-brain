---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-624"
status: "Stable"
---
# CAPEC-624: Hardware Fault Injection

**Abstraction:** Meta  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

The adversary uses disruptive signals or events, or alters the physical environment a device operates in, to cause faulty behavior in electronic devices. This can include electromagnetic pulses, laser pulses, clock glitches, ambient temperature extremes, and more. When performed in a controlled manner on devices performing cryptographic operations, this faulty behavior can be exploited to derive secret key information.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-624 on capec.mitre.org](https://capec.mitre.org/data/definitions/624.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
