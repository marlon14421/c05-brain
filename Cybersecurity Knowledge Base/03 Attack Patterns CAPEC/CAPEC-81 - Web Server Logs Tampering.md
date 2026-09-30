---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-81"
status: "Draft"
---
# CAPEC-81: Web Server Logs Tampering

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

Web Logs Tampering attacks involve an attacker injecting, deleting or otherwise tampering with the contents of web logs typically for the purposes of masking other malicious behavior. Additionally, writing malicious data to log files may target jobs, filters, reports, and other agents that process the logs in an asynchronous attack pattern. This pattern of attack is similar to "Log Injection-Tampering-Forging" except that in this case, the attack is targeting the logs of the web server and not the application.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-81 on capec.mitre.org](https://capec.mitre.org/data/definitions/81.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
