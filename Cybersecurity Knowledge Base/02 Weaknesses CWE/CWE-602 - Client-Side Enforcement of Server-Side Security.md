---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-602"
status: "Draft"
---
# CWE-602: Client-Side Enforcement of Server-Side Security

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, ICS/OT, Mobile

## Description

The product is composed of a server that relies on the client to implement a mechanism that is intended to protect the server.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** If some degree of trust is required between the two entities, then use integrity checking and strong authentication to ensure that the inputs are coming from a trusted source. Design the product so that this trust is managed in a centralized fashion, especially if there are complex or numerous communication channels, in order to reduce the risks that the implementer will mistakenly omit a check in a single code path.

## Related weaknesses

- CWE-693 (ChildOf)
- CWE-471 (CanPrecede)
- CWE-290 (PeerOf)
- CWE-300 (PeerOf)

## Source

- [CWE-602 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/602.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
