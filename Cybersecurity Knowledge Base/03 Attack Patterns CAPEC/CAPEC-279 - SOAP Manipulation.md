---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-279"
status: "Draft"
---
# CAPEC-279: SOAP Manipulation

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

Simple Object Access Protocol (SOAP) is used as a communication protocol between a client and server to invoke web services on the server. It is an XML-based protocol, and therefore suffers from many of the same shortcomings as other XML-based protocols. Adversaries can make use of these shortcomings and manipulate the content of SOAP paramters, leading to undesirable behavior on the server and allowing the adversary to carry out a number of further attacks.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-279 on capec.mitre.org](https://capec.mitre.org/data/definitions/279.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
