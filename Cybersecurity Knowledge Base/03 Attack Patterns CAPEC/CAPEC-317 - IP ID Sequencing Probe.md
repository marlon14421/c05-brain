---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-317"
status: "Stable"
---
# CAPEC-317: IP ID Sequencing Probe

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

This OS fingerprinting probe analyzes the IP 'ID' field sequence number generation algorithm of a remote host. Operating systems generate IP 'ID' numbers differently, allowing an attacker to identify the operating system of the host by examining how is assigns ID numbers when generating response packets. RFC 791 does not specify how ID numbers are chosen or their ranges, so ID sequence generation differs from implementation to implementation. There are two kinds of IP 'ID' sequence number analysis - IP 'ID' Sequencing: analyzing the IP 'ID' sequence generation algorithm for one protocol used by a host and Shared IP 'ID' Sequencing: analyzing the packet ordering via IP 'ID' values spanning multiple protocols, such as between ICMP and TCP.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-317 on capec.mitre.org](https://capec.mitre.org/data/definitions/317.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
