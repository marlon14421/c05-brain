---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-517"
status: "Draft"
---
# CAPEC-517: Documentation Alteration to Circumvent Dial-down

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An attacker with access to a manufacturer's documentation, which include descriptions of advanced technology and/or specific components' criticality, alters the documents to circumvent dial-down functionality requirements. This alteration would change the interpretation of implementation and manufacturing techniques, allowing for advanced technologies to remain in place even though these technologies might be restricted to certain customers, such as nations on the terrorist watch list, giving the attacker on the receiving end of a shipped product access to an advanced technology that might otherwise be restricted.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-517 on capec.mitre.org](https://capec.mitre.org/data/definitions/517.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
