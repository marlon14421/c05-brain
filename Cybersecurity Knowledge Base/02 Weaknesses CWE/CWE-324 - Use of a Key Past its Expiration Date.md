---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-324"
status: "Draft"
---
# CWE-324: Use of a Key Past its Expiration Date

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses a cryptographic key or password past its expiration date, which diminishes its safety significantly by increasing the timing window for cracking attacks against that key.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Adequate consideration should be put in to the user interface in order to notify users previous to the key's expiration, to explain the importance of new key generation and to walk users through the process as painlessly as possible.

## Related weaknesses

- CWE-672 (ChildOf)
- CWE-298 (PeerOf)

## Source

- [CWE-324 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/324.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
