---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-322"
status: "Draft"
---
# CWE-322: Key Exchange without Entity Authentication

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product performs a key exchange with an actor without verifying the identity of that actor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that proper authentication is included in the system design.
- **Implementation:** Understand and properly implement all checks necessary to ensure the identity of entities involved in encrypted communications.

## Related weaknesses

- CWE-306 (ChildOf)
- CWE-923 (CanPrecede)
- CWE-295 (PeerOf)

## Source

- [CWE-322 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/322.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
