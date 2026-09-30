---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-579"
status: "Draft"
---
# CWE-579: J2EE Bad Practices: Non-serializable Object Stored in Session

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product stores a non-serializable object as an HttpSession attribute, which can hurt reliability.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** In order for session replication to work, the values the product stores as attributes in the session must implement the Serializable interface.

## Related weaknesses

- CWE-573 (ChildOf)

## Source

- [CWE-579 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/579.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
