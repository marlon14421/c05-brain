---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-158"
status: "Draft"
---
# CAPEC-158: Sniffing Network Traffic

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

In this attack pattern, the adversary monitors network traffic between nodes of a public or multicast network in an attempt to capture sensitive information at the protocol level. Network sniffing applications can reveal TCP/IP, DNS, Ethernet, and other low-level network communication information. The adversary takes a passive role in this attack pattern and simply observes and analyzes the traffic. The adversary may precipitate or indirectly influence the content of the observed transaction, but is never the intended recipient of the target information.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-158 on capec.mitre.org](https://capec.mitre.org/data/definitions/158.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
