---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-580"
status: "Draft"
---
# CWE-580: clone() Method Without super.clone()

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product contains a clone() method that does not call super.clone() to obtain the new object.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Call super.clone() within your clone() method, when obtaining a new object.
- **Implementation:** In some cases, you can eliminate the clone method altogether and use copy constructors.

## Related weaknesses

- CWE-664 (ChildOf)
- CWE-573 (ChildOf)

## Source

- [CWE-580 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/580.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
