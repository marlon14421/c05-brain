---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-574"
status: "Stable"
---
# CAPEC-574: Services Footprinting

**Abstraction:** Standard  
**Catalog severity:** Low  
**Catalog likelihood:** Low

## Description

An adversary exploits functionality meant to identify information about the services on the target system to an authorized user. By knowing what services are registered on the target system, the adversary can learn about the target environment as a means towards further malicious behavior. Depending on the operating system, commands that can obtain services information include "sc" and "tasklist/svc" using Tasklist, and "net start" using Net.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-574 on capec.mitre.org](https://capec.mitre.org/data/definitions/574.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
