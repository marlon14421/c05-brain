---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-181"
status: "Draft"
---
# CAPEC-181: Flash File Overlay

**Abstraction:** Detailed  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

An attacker creates a transparent overlay using flash in order to intercept user actions for the purpose of performing a clickjacking attack. In this technique, the Flash file provides a transparent overlay over HTML content. Because the Flash application is on top of the content, user actions, such as clicks, are caught by the Flash application rather than the underlying HTML. The action is then interpreted by the overlay to perform the actions the attacker wishes.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-181 on capec.mitre.org](https://capec.mitre.org/data/definitions/181.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
