---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-319"
status: "Stable"
---
# CAPEC-319: IP (DF) 'Don't Fragment Bit' Echoing Probe

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

This OS fingerprinting probe tests to determine if the remote host echoes back the IP 'DF' (Don't Fragment) bit in a response packet. An attacker sends a UDP datagram with the DF bit set to a closed port on the remote host to observe whether the 'DF' bit is set in the response packet. Some operating systems will echo the bit in the ICMP error message while others will zero out the bit in the response packet.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-319 on capec.mitre.org](https://capec.mitre.org/data/definitions/319.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
