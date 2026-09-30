---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-66"
status: "Draft"
---
# CAPEC-66: SQL Injection

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This attack exploits target software that constructs SQL statements based on user input. An attacker crafts input strings so that when the target software constructs SQL statements based on the input, the resulting SQL statement performs actions other than those the application intended. SQL Injection results from failure of the application to appropriately validate input.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-66 on capec.mitre.org](https://capec.mitre.org/data/definitions/66.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
