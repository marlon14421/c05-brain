---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-646"
status: "Stable"
---
# CAPEC-646: Peripheral Footprinting

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** Low

## Description

Adversaries may attempt to obtain information about attached peripheral devices and components connected to a computer system. Examples may include discovering the presence of iOS devices by searching for backups, analyzing the Windows registry to determine what USB devices have been connected, or infecting a victim system with malware to report when a USB device has been connected. This may allow the adversary to gain additional insight about the system or network environment, which may be useful in constructing further attacks.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-646 on capec.mitre.org](https://capec.mitre.org/data/definitions/646.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
