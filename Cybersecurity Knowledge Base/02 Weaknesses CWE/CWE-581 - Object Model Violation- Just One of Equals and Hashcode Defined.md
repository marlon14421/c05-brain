---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-581"
status: "Draft"
---
# CWE-581: Object Model Violation: Just One of Equals and Hashcode Defined

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product does not maintain equal hashcodes for equal objects.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Both Equals() and Hashcode() should be defined.

## Related weaknesses

- CWE-573 (ChildOf)
- CWE-697 (ChildOf)

## Source

- [CWE-581 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/581.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
