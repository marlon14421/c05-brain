---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-468"
status: "Incomplete"
---
# CWE-468: Incorrect Pointer Scaling

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

In C and C++, one may often accidentally refer to the wrong memory due to the semantics of when math operations are implicitly scaled.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a platform with high-level memory abstractions.
- **Implementation:** Always use array indexing instead of direct pointer manipulation.
- **Architecture and Design:** Use technologies for preventing buffer overflows.

## Related weaknesses

- CWE-682 (ChildOf)

## Source

- [CWE-468 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/468.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
