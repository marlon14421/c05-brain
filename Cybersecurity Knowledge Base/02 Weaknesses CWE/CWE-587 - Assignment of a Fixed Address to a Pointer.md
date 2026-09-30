---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-587"
status: "Draft"
---
# CWE-587: Assignment of a Fixed Address to a Pointer

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++, C#, Assembly

## Description

The product sets a pointer to a specific address other than NULL or 0.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Never set a pointer to a fixed address.

## Related weaknesses

- CWE-344 (ChildOf)
- CWE-758 (ChildOf)

## Source

- [CWE-587 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/587.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
