---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-401"
status: "Draft"
---
# CWE-401: Missing Release of Memory after Effective Lifetime

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, C, C++

## Description

The product does not sufficiently track and release allocated memory after it has been used, making the memory unavailable for reallocation and reuse.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use an abstraction library to abstract away risky APIs. Not a complete solution.
- **Architecture and Design:** Consider using the Boehm-Demers-Weiser garbage collector (bdwgc), which can help avoid leaks.

## Related weaknesses

- CWE-772 (ChildOf)
- CWE-404 (ChildOf)
- CWE-404 (ChildOf)

## Source

- [CWE-401 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/401.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
