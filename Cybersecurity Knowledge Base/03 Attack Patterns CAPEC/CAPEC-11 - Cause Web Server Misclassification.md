---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-11"
status: "Draft"
---
# CAPEC-11: Cause Web Server Misclassification

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

An attack of this type exploits a Web server's decision to take action based on filename or file extension. Because different file types are handled by different server processes, misclassification may force the Web server to take unexpected action, or expected actions in an unexpected sequence. This may cause the server to exhaust resources, supply debug or system data to the attacker, or bind an attacker to a remote process.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-11 on capec.mitre.org](https://capec.mitre.org/data/definitions/11.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
