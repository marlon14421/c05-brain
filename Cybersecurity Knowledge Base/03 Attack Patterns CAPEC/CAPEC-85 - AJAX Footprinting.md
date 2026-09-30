---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-85"
status: "Draft"
---
# CAPEC-85: AJAX Footprinting

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** High

## Description

This attack utilizes the frequent client-server roundtrips in Ajax conversation to scan a system. While Ajax does not open up new vulnerabilities per se, it does optimize them from an attacker point of view. A common first step for an attacker is to footprint the target environment to understand what attacks will work. Since footprinting relies on enumeration, the conversational pattern of rapid, multiple requests and responses that are typical in Ajax applications enable an attacker to look for many vulnerabilities, well-known ports, network locations and so on. The knowledge gained through Ajax fingerprinting can be used to support other attacks, such as XSS.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-85 on capec.mitre.org](https://capec.mitre.org/data/definitions/85.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
