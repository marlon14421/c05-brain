---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-124"
status: "Incomplete"
---
# CWE-124: Buffer Underwrite ('Buffer Underflow')

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product writes to a buffer using an index or pointer that references a memory location prior to the beginning of the buffer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Choose a language that is not susceptible to these issues.
- **Implementation:** All calculated values that are used as index or for pointer arithmetic should be validated to ensure that they are within an expected range.

## Related weaknesses

- CWE-786 (ChildOf)
- CWE-787 (ChildOf)

## Source

- [CWE-124 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/124.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
