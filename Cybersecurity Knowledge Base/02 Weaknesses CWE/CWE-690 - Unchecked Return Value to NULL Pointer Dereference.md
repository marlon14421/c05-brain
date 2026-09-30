---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-690"
status: "Draft"
---
# CWE-690: Unchecked Return Value to NULL Pointer Dereference

**Abstraction:** Compound  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product does not check for an error after calling a function that can return with a NULL pointer if the function fails, which leads to a resultant NULL pointer dereference.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-252 (StartsWith)
- CWE-252 (ChildOf)

## Source

- [CWE-690 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/690.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
