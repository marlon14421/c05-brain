---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-328"
status: "Stable"
---
# CAPEC-328: TCP 'RST' Flag Checksum Probe

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

This OS fingerprinting probe performs a checksum on any ASCII data contained within the data portion or a RST packet. Some operating systems will report a human-readable text message in the payload of a 'RST' (reset) packet when specific types of connection errors occur. RFC 1122 allows text payloads within reset packets but not all operating systems or routers implement this functionality.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-328 on capec.mitre.org](https://capec.mitre.org/data/definitions/328.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
