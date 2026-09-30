---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-839"
status: "Incomplete"
---
# CWE-839: Numeric Range Comparison Without Minimum Check

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

The product checks a value to ensure that it is less than or equal to a maximum, but it does not also verify that the value is greater than or equal to the minimum.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If the number to be used is always expected to be positive, change the variable type from signed to unsigned or size_t.
- **Implementation:** If the number to be used could have a negative value based on the specification (thus requiring a signed value), but the number should only be positive to preserve code correctness, then include a check to ensure that the value is positive.

## Related weaknesses

- CWE-1023 (ChildOf)
- CWE-195 (CanPrecede)
- CWE-682 (CanPrecede)
- CWE-119 (CanPrecede)
- CWE-124 (CanPrecede)

## Source

- [CWE-839 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/839.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
