---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-39"
status: "Draft"
---
# CAPEC-39: Manipulating Opaque Client-based Data Tokens

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** High

## Description

In circumstances where an application holds important data client-side in tokens (cookies, URLs, data files, and so forth) that data can be manipulated. If client or server-side application components reinterpret that data as authentication tokens or data (such as store item pricing or wallet information) then even opaquely manipulating that data may bear fruit for an Attacker. In this pattern an attacker undermines the assumption that client side tokens have been adequately protected from tampering through use of encryption or obfuscation.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-39 on capec.mitre.org](https://capec.mitre.org/data/definitions/39.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
