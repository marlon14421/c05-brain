---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-110"
status: "Draft"
---
# CAPEC-110: SQL Injection through SOAP Parameter Tampering

**Abstraction:** Detailed  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

An attacker modifies the parameters of the SOAP message that is sent from the service consumer to the service provider to initiate a SQL injection attack. On the service provider side, the SOAP message is parsed and parameters are not properly validated before being used to access a database in a way that does not use parameter binding, thus enabling the attacker to control the structure of the executed SQL query. This pattern describes a SQL injection attack with the delivery mechanism being a SOAP message.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-110 on capec.mitre.org](https://capec.mitre.org/data/definitions/110.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
