---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-528"
status: "Draft"
---
# CAPEC-528: XML Flood

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** Low

## Description

An adversary may execute a flooding attack using XML messages with the intent to deny legitimate users access to a web service. These attacks are accomplished by sending a large number of XML based requests and letting the service attempt to parse each one. In many cases this type of an attack will result in a XML Denial of Service (XDoS) due to an application becoming unstable, freezing, or crashing.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-528 on capec.mitre.org](https://capec.mitre.org/data/definitions/528.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
