---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-276"
status: "Draft"
---
# CAPEC-276: Inter-component Protocol Manipulation

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

Inter-component protocols are used to communicate between different software and hardware modules within a single computer. Common examples are: interrupt signals and data pipes. Subverting the protocol can allow an adversary to impersonate others, discover sensitive information, control the outcome of a session, or perform other attacks. This type of attack targets invalid assumptions that may be inherent in implementers of the protocol, incorrect implementations of the protocol, or vulnerabilities in the protocol itself.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-276 on capec.mitre.org](https://capec.mitre.org/data/definitions/276.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
