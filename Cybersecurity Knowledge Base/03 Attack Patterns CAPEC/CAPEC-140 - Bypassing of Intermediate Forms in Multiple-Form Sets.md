---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-140"
status: "Draft"
---
# CAPEC-140: Bypassing of Intermediate Forms in Multiple-Form Sets

**Abstraction:** Standard  
**Catalog severity:** Medium  
**Catalog likelihood:** Not stated

## Description

Some web applications require users to submit information through an ordered sequence of web forms. This is often done if there is a very large amount of information being collected or if information on earlier forms is used to pre-populate fields or determine which additional information the application needs to collect. An attacker who knows the names of the various forms in the sequence may be able to explicitly type in the name of a later form and navigate to it without first going through the previous forms. This can result in incomplete collection of information, incorrect assumptions about the information submitted by the attacker, or other problems that can impair the functioning of the application.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-140 on capec.mitre.org](https://capec.mitre.org/data/definitions/140.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
