---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-353"
status: "Draft"
---
# CWE-353: Missing Support for Integrity Check

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses a transmission protocol that does not include a mechanism for verifying the integrity of the data during transmission, such as a checksum.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Add an appropriately sized checksum to the protocol, ensuring that data received may be simply validated before it is parsed and used.
- **Implementation:** Ensure that the checksums present in the protocol design are properly implemented and added to each message before it is sent.

## Related weaknesses

- CWE-345 (ChildOf)
- CWE-354 (PeerOf)

## Source

- [CWE-353 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/353.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
