---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-194"
status: "Incomplete"
---
# CWE-194: Unexpected Sign Extension

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

The product performs an operation on a number that causes it to be sign extended when it is transformed into a larger data type. When the original number is negative, this can produce unexpected values that lead to resultant weaknesses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Avoid using signed variables if you don't need to represent negative values. When negative values are needed, perform validation after you save those values to larger data types, or before passing them to functions that are expecting unsigned values.

## Related weaknesses

- CWE-681 (ChildOf)
- CWE-681 (ChildOf)
- CWE-681 (ChildOf)

## Source

- [CWE-194 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/194.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
