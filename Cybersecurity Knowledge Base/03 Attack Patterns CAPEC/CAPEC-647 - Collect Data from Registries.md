---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-647"
status: "Draft"
---
# CAPEC-647: Collect Data from Registries

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Medium

## Description

An adversary exploits a weakness in authorization to gather system-specific data and sensitive information within a registry (e.g., Windows Registry, Mac plist). These contain information about the system configuration, software, operating system, and security. The adversary can leverage information gathered in order to carry out further attacks.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-647 on capec.mitre.org](https://capec.mitre.org/data/definitions/647.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
