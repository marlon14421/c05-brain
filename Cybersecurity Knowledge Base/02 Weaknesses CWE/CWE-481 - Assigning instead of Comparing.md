---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-481"
status: "Draft"
---
# CWE-481: Assigning instead of Comparing

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Java, C#

## Description

The code uses an operator for assignment when the intention was to perform a comparison.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Place constants on the left. If one attempts to assign a constant with a variable, the compiler will produce an error.

## Related weaknesses

- CWE-480 (ChildOf)
- CWE-697 (CanPrecede)

## Source

- [CWE-481 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/481.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
