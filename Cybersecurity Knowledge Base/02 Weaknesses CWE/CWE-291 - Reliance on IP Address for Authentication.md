---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-291"
status: "Incomplete"
---
# CWE-291: Reliance on IP Address for Authentication

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses an IP address for authentication.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use other means of identity verification that cannot be simply spoofed. Possibilities include a username/password or certificate.

## Related weaknesses

- CWE-290 (ChildOf)
- CWE-923 (ChildOf)

## Source

- [CWE-291 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/291.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
