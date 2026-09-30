---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-32"
status: "Draft"
---
# CAPEC-32: XSS Through HTTP Query Strings

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

An adversary embeds malicious script code in the parameters of an HTTP query string and convinces a victim to submit the HTTP request that contains the query string to a vulnerable web application. The web application then procedes to use the values parameters without properly validation them first and generates the HTML code that will be executed by the victim's browser.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-32 on capec.mitre.org](https://capec.mitre.org/data/definitions/32.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
