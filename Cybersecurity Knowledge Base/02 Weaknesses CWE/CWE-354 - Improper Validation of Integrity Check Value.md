---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-354"
status: "Draft"
---
# CWE-354: Improper Validation of Integrity Check Value

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not validate or incorrectly validates the integrity check values or "checksums" of a message. This may prevent it from detecting if the data has been modified or corrupted in transmission.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that the checksums present in messages are properly checked in accordance with the protocol specification before they are parsed and used.

## Related weaknesses

- CWE-345 (ChildOf)
- CWE-345 (ChildOf)
- CWE-754 (ChildOf)
- CWE-353 (PeerOf)

## Source

- [CWE-354 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/354.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
