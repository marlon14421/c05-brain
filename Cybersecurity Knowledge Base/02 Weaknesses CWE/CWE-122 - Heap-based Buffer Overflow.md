---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-122"
status: "Draft"
---
# CWE-122: Heap-based Buffer Overflow

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++, Not Technology-Specific

## Description

A heap overflow condition is a buffer overflow, where the buffer that can be overwritten is allocated in the heap portion of memory, generally meaning that the buffer was allocated using a routine such as malloc().

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Mitigation:** Pre-design: Use a language or compiler that performs automatic bounds checking.
- **Architecture and Design:** Use an abstraction library to abstract away risky APIs. Not a complete solution.
- **Implementation:** Implement and perform bounds checking on input.
- **Implementation:** Do not use dangerous functions such as gets. Look for their safe equivalent, which checks for the boundary.
- **Operation:** Use OS-level preventative functionality. This is not a complete solution, but it provides some defense in depth.

## Related weaknesses

- CWE-788 (ChildOf)
- CWE-787 (ChildOf)

## Source

- [CWE-122 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/122.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
