---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-590"
status: "Incomplete"
---
# CWE-590: Free of Memory not on the Heap

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Memory-Unsafe, C

## Description

The product calls free() on a pointer to memory that was not allocated using associated heap allocation functions such as malloc(), calloc(), or realloc().

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Only free pointers that you have called malloc on previously. This is the recommended solution. Keep track of which pointers point at the beginning of valid chunks and free them only once.
- **Implementation:** Before freeing a pointer, the programmer should make sure that the pointer was previously allocated on the heap and that the memory belongs to the programmer. Freeing an unallocated pointer will cause undefined behavior in the program.
- **Architecture and Design:** Use a language that provides abstractions for memory allocation and deallocation.

## Related weaknesses

- CWE-762 (ChildOf)
- CWE-123 (CanPrecede)

## Source

- [CWE-590 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/590.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
