---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-174"
status: "Draft"
---
# CAPEC-174: Flash Parameter Injection

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** High

## Description

An adversary takes advantage of improper data validation to inject malicious global parameters into a Flash file embedded within an HTML document. Flash files can leverage user-submitted data to configure the Flash document and access the embedding HTML document.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-174 on capec.mitre.org](https://capec.mitre.org/data/definitions/174.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
