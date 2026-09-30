---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-155"
status: "Draft"
---
# CAPEC-155: Screen Temporary Files for Sensitive Information

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Medium

## Description

An adversary exploits the temporary, insecure storage of information by monitoring the content of files used to store temp data during an application's routine execution flow. Many applications use temporary files to accelerate processing or to provide records of state across multiple executions of the application. Sometimes, however, these temporary files may end up storing sensitive information. By screening an application's temporary files, an adversary might be able to discover such sensitive information. For example, web browsers often cache content to accelerate subsequent lookups. If the content contains sensitive information then the adversary could recover this from the web cache.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-155 on capec.mitre.org](https://capec.mitre.org/data/definitions/155.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
