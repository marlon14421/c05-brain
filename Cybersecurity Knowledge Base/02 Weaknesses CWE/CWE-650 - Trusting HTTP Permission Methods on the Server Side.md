---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-650"
status: "Incomplete"
---
# CWE-650: Trusting HTTP Permission Methods on the Server Side

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The server contains a protection mechanism that assumes that any URI that is accessed using HTTP GET will not cause a state change to the associated resource. This might allow attackers to bypass intended access restrictions and conduct resource modification and deletion attacks, since some applications allow GET to modify state.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Configure ACLs on the server side to ensure that proper level of access control is defined for each accessible resource representation.

## Related weaknesses

- CWE-436 (ChildOf)

## Source

- [CWE-650 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/650.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
