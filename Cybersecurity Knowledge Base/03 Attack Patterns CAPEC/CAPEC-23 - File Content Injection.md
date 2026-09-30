---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-23"
status: "Draft"
---
# CAPEC-23: File Content Injection

**Abstraction:** Standard  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

An adversary poisons files with a malicious payload (targeting the file systems accessible by the target software), which may be passed through by standard channels such as via email, and standard web content like PDF and multimedia files. The adversary exploits known vulnerabilities or handling routines in the target processes, in order to exploit the host's trust in executing remote content, including binary files.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-23 on capec.mitre.org](https://capec.mitre.org/data/definitions/23.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
