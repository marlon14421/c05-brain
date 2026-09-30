---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-275"
status: "Draft"
---
# CAPEC-275: DNS Rebinding

**Abstraction:** Detailed  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

An adversary serves content whose IP address is resolved by a DNS server that the adversary controls. After initial contact by a web browser (or similar client), the adversary changes the IP address to which its name resolves, to an address within the target organization that is not publicly accessible. This allows the web browser to examine this internal address on behalf of the adversary.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-275 on capec.mitre.org](https://capec.mitre.org/data/definitions/275.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
