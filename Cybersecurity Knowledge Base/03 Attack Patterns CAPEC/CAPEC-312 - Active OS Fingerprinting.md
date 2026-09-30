---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-312"
status: "Stable"
---
# CAPEC-312: Active OS Fingerprinting

**Abstraction:** Standard  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

An adversary engages in activity to detect the operating system or firmware version of a remote target by interrogating a device, server, or platform with a probe designed to solicit behavior that will reveal information about the operating systems or firmware in the environment. Operating System detection is possible because implementations of common protocols (Such as IP or TCP) differ in distinct ways. While the implementation differences are not sufficient to 'break' compatibility with the protocol the differences are detectable because the target will respond in unique ways to specific probing activity that breaks the semantic or logical rules of packet construction for a protocol. Different operating systems will have a unique response to the anomalous input, providing the basis to fingerprint the OS behavior. This type of OS fingerprinting can distinguish between operating system types and versions.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-312 on capec.mitre.org](https://capec.mitre.org/data/definitions/312.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
