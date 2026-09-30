---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-596"
status: "Draft"
---
# CAPEC-596: TCP RST Injection

**Abstraction:** Detailed  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary injects one or more TCP RST packets to a target after the target has made a HTTP GET request. The goal of this attack is to have the target and/or destination web server terminate the TCP connection.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-596 on capec.mitre.org](https://capec.mitre.org/data/definitions/596.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
