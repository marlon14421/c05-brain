---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-416"
status: "Stable"
---
# CWE-416: Use After Free

**Abstraction:** Variant  
**Status in catalog:** Stable  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product reuses or references memory after it has been freed. At some point afterward, the memory may be allocated again and saved in another pointer, while the original pointer references a location somewhere within the new allocation. Any operations using the original pointer are no longer valid because the memory "belongs" to the code that operates on the new pointer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Choose a language that provides automatic memory management.
- **Implementation:** When freeing pointers, be sure to set them to NULL once they are freed. However, the utilization of multiple or complex data structures may lower the usefulness of this strategy.

## Related weaknesses

- CWE-825 (ChildOf)
- CWE-672 (ChildOf)
- CWE-672 (ChildOf)
- CWE-672 (ChildOf)
- CWE-120 (CanPrecede)
- CWE-123 (CanPrecede)

## Source

- [CWE-416 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/416.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
