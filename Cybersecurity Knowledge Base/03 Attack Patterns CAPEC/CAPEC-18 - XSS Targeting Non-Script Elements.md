---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-18"
status: "Draft"
---
# CAPEC-18: XSS Targeting Non-Script Elements

**Abstraction:** Detailed  
**Catalog severity:** Very High  
**Catalog likelihood:** High

## Description

This attack is a form of Cross-Site Scripting (XSS) where malicious scripts are embedded in elements that are not expected to host scripts such as image tags ( ), comments in XML documents ( ), etc. These tags may not be subject to the same input validation, output validation, and other content filtering and checking routines, so this can create an opportunity for an adversary to tunnel through the application's elements and launch a XSS attack through other elements. As with all remote attacks, it is important to differentiate the ability to launch an attack (such as probing an internal network for unpatched servers) and the ability of the remote adversary to collect and interpret the output of said attack.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-18 on capec.mitre.org](https://capec.mitre.org/data/definitions/18.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
