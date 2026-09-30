---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-322"
status: "Stable"
---
# CAPEC-322: TCP (ISN) Greatest Common Divisor Probe

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

This OS fingerprinting probe sends a number of TCP SYN packets to an open port of a remote machine. The Initial Sequence Number (ISN) in each of the SYN/ACK response packets is analyzed to determine the smallest number that the target host uses when incrementing sequence numbers. This information can be useful for identifying an operating system because particular operating systems and versions increment sequence numbers using different values. The result of the analysis is then compared against a database of OS behaviors to determine the OS type and/or version.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-322 on capec.mitre.org](https://capec.mitre.org/data/definitions/322.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
