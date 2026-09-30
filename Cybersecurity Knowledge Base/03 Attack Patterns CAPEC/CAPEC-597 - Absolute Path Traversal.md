---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-597"
status: "Draft"
---
# CAPEC-597: Absolute Path Traversal

**Abstraction:** Detailed  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary with access to file system resources, either directly or via application logic, will use various file absolute paths and navigation mechanisms such as ".." to extend their range of access to inappropriate areas of the file system. The goal of the adversary is to access directories and files that are intended to be restricted from their access.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-597 on capec.mitre.org](https://capec.mitre.org/data/definitions/597.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
