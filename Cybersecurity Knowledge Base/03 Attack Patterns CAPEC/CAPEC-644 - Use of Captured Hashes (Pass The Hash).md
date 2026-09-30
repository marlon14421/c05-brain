---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-644"
status: "Stable"
---
# CAPEC-644: Use of Captured Hashes (Pass The Hash)

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

An adversary obtains (i.e. steals or purchases) legitimate Windows domain credential hash values to access systems within the domain that leverage the Lan Man (LM) and/or NT Lan Man (NTLM) authentication protocols.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-644 on capec.mitre.org](https://capec.mitre.org/data/definitions/644.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
