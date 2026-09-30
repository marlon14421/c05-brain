---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-627"
status: "Draft"
---
# CAPEC-627: Counterfeit GPS Signals

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An adversary attempts to deceive a GPS receiver by broadcasting counterfeit GPS signals, structured to resemble a set of normal GPS signals. These spoofed signals may be structured in such a way as to cause the receiver to estimate its position to be somewhere other than where it actually is, or to be located where it is but at a different time, as determined by the adversary.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-627 on capec.mitre.org](https://capec.mitre.org/data/definitions/627.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
