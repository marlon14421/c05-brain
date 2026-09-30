---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-88"
status: "Draft"
---
# CAPEC-88: OS Command Injection

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

In this type of an attack, an adversary injects operating system commands into existing application functions. An application that uses untrusted input to build command strings is vulnerable. An adversary can leverage OS command injection in an application to elevate privileges, execute arbitrary commands and compromise the underlying operating system.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-88 on capec.mitre.org](https://capec.mitre.org/data/definitions/88.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
