---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-546"
status: "Draft"
---
# CAPEC-546: Incomplete Data Deletion in a Multi-Tenant Environment

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Low

## Description

An adversary obtains unauthorized information due to insecure or incomplete data deletion in a multi-tenant environment. If a cloud provider fails to completely delete storage and data from former cloud tenants' systems/resources, once these resources are allocated to new, potentially malicious tenants, the latter can probe the provided resources for sensitive information still there.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-546 on capec.mitre.org](https://capec.mitre.org/data/definitions/546.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
