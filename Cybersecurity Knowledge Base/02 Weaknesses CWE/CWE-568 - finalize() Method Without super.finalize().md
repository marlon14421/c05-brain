---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-568"
status: "Draft"
---
# CWE-568: finalize() Method Without super.finalize()

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product contains a finalize() method that does not call super.finalize().

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Call the super.finalize() method.

## Related weaknesses

- CWE-573 (ChildOf)
- CWE-459 (ChildOf)

## Source

- [CWE-568 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/568.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
