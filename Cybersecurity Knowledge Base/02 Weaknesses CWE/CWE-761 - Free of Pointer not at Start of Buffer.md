---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-761"
status: "Incomplete"
---
# CWE-761: Free of Pointer not at Start of Buffer

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Memory-Unsafe, C

## Description

The product calls free() on a pointer to a memory resource that was allocated on the heap, but the pointer is not at the start of the buffer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When utilizing pointer arithmetic to traverse a buffer, use a separate variable to track progress through memory and preserve the originally allocated address for later freeing.
- **Implementation:** When programming in C++, consider using smart pointers provided by the boost library to help correctly and consistently manage memory.
- **Architecture and Design:** Use a language that provides abstractions for memory allocation and deallocation.

## Related weaknesses

- CWE-763 (ChildOf)
- CWE-404 (ChildOf)

## Source

- [CWE-761 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/761.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
