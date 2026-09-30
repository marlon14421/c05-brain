---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1263"
status: "Incomplete"
---
# CWE-1263: Improper Physical Access Control

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product is designed with access restricted to certain information, but it does not sufficiently protect against an unauthorized actor with physical access to these areas.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Specific protection requirements depend strongly on contextual factors including the level of acceptable risk associated with compromise to the product's protection mechanism. Designers could incorporate anti-tampering measures that protect against or detect when the product has been tampered with.
- **Testing:** The testing phase of the lifecycle should establish a method for determining whether the protection mechanism is sufficient to prevent unauthorized access.
- **Manufacturing:** Ensure that all protection mechanisms are fully activated at the time of manufacturing and distribution.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-1191 (PeerOf)

## Source

- [CWE-1263 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1263.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
