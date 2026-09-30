---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-637"
status: "Stable"
---
# CAPEC-637: Collect Data from Clipboard

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Low

## Description

The adversary exploits an application that allows for the copying of sensitive data or information by collecting information copied to the clipboard. Data copied to the clipboard can be accessed by other applications, such as malware built to exfiltrate or log clipboard contents on a periodic basis. In this way, the adversary aims to garner information to which they are unauthorized.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-637 on capec.mitre.org](https://capec.mitre.org/data/definitions/637.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
