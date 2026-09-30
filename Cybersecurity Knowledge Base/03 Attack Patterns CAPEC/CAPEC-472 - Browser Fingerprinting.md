---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-472"
status: "Draft"
---
# CAPEC-472: Browser Fingerprinting

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An attacker carefully crafts small snippets of Java Script to efficiently detect the type of browser the potential victim is using. Many web-based attacks need prior knowledge of the web browser including the version of browser to ensure successful exploitation of a vulnerability. Having this knowledge allows an attacker to target the victim with attacks that specifically exploit known or zero day weaknesses in the type and version of the browser used by the victim. Automating this process via Java Script as a part of the same delivery system used to exploit the browser is considered more efficient as the attacker can supply a browser fingerprinting method and integrate it with exploit code, all contained in Java Script and in response to the same web page request by the browser.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-472 on capec.mitre.org](https://capec.mitre.org/data/definitions/472.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
