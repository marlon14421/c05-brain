---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-77"
status: "Draft"
---
# CAPEC-77: Manipulating User-Controlled Variables

**Abstraction:** Standard  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

This attack targets user controlled variables (DEBUG=1, PHP Globals, and So Forth). An adversary can override variables leveraging user-supplied, untrusted query variables directly used on the application server without any data sanitization. In extreme cases, the adversary can change variables controlling the business logic of the application. For instance, in languages like PHP, a number of poorly set default configurations may allow the user to override variables.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-77 on capec.mitre.org](https://capec.mitre.org/data/definitions/77.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
