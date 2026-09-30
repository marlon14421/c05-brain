---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-325"
status: "Stable"
---
# CAPEC-325: TCP Congestion Control Flag (ECN) Probe

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

This OS fingerprinting probe checks to see if the remote host supports explicit congestion notification (ECN) messaging. ECN messaging was designed to allow routers to notify a remote host when signal congestion problems are occurring. Explicit Congestion Notification messaging is defined by RFC 3168. Different operating systems and versions may or may not implement ECN notifications, or may respond uniquely to particular ECN flag types.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-325 on capec.mitre.org](https://capec.mitre.org/data/definitions/325.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
