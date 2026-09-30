---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-301"
status: "Stable"
---
# CAPEC-301: TCP Connect Scan

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An adversary uses full TCP connection attempts to determine if a port is open on the target system. The scanning process involves completing a 'three-way handshake' with a remote port, and reports the port as closed if the full handshake cannot be established. An advantage of TCP connect scanning is that it works against any TCP/IP stack.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-301 on capec.mitre.org](https://capec.mitre.org/data/definitions/301.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
