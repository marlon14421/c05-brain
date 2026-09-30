---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-447"
status: "Stable"
---
# CAPEC-447: Design Alteration

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

An adversary modifies the design of a technology, product, or component to acheive a negative impact once the system is deployed. In this type of attack, the goal of the adversary is to modify the design of the system, prior to development starting, in such a way that the negative impact can be leveraged when the system is later deployed. Design alteration attacks differ from development alteration attacks in that design alteration attacks take place prior to development and which then may or may not be developed by the adverary. Design alteration attacks include modifying system designs to degrade system performance, cause unexpected states or errors, and general design changes that may lead to additional vulnerabilities. These attacks generally require insider access to modify design documents, but they may also be spoofed via web communications. The product is then developed and delivered to the user where the negative impact can be leveraged at a later time.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-447 on capec.mitre.org](https://capec.mitre.org/data/definitions/447.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
