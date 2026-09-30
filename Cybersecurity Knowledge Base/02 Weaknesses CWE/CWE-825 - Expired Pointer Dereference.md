---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-825"
status: "Incomplete"
---
# CWE-825: Expired Pointer Dereference

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product dereferences a pointer that contains a location for memory that was previously valid, but is no longer valid.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Choose a language that provides automatic memory management.
- **Implementation:** When freeing pointers, be sure to set them to NULL once they are freed. However, the utilization of multiple or complex data structures may lower the usefulness of this strategy.

## Related weaknesses

- CWE-119 (ChildOf)
- CWE-119 (ChildOf)
- CWE-119 (ChildOf)
- CWE-672 (ChildOf)
- CWE-125 (CanPrecede)
- CWE-787 (CanPrecede)

## Source

- [CWE-825 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/825.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
