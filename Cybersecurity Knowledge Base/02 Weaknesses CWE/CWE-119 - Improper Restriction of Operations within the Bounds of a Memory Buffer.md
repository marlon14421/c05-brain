---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-119"
status: "Stable"
---
# CWE-119: Improper Restriction of Operations within the Bounds of a Memory Buffer

**Abstraction:** Class  
**Status in catalog:** Stable  
**Applicable platforms:** Memory-Unsafe, C, C++, Assembly, Not Technology-Specific

## Description

The product performs operations on a memory buffer, but it reads from or writes to a memory location outside the buffer's intended boundary. This may result in read or write operations on unexpected memory locations that could be linked to other variables, data structures, or internal program data.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Replace unbounded copy functions with analogous functions that support length arguments, such as strcpy with strncpy. Create these if they are not available.

## Related weaknesses

- CWE-118 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-119 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/119.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
