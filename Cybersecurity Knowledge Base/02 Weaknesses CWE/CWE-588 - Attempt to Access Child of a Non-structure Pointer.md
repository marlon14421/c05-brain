---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-588"
status: "Incomplete"
---
# CWE-588: Attempt to Access Child of a Non-structure Pointer

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

Casting a non-structure type to a structure type and accessing a field can lead to memory access errors or data corruption.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** The choice could be made to use a language that is not susceptible to these issues.
- **Implementation:** Review of type casting operations can identify locations where incompatible types are cast.

## Related weaknesses

- CWE-704 (ChildOf)
- CWE-758 (ChildOf)

## Source

- [CWE-588 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/588.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
