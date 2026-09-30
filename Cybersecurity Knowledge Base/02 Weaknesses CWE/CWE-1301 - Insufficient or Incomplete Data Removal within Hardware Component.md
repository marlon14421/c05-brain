---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1301"
status: "Incomplete"
---
# CWE-1301: Insufficient or Incomplete Data Removal within Hardware Component

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product's data removal process does not completely delete all data and potentially sensitive information within hardware components.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Apply blinding or masking techniques to implementations of cryptographic algorithms.
- **Implementation:** Alter the method of erasure, add protection of media, or destroy the media to protect the data.

## Related weaknesses

- CWE-226 (ChildOf)

## Source

- [CWE-1301 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1301.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
