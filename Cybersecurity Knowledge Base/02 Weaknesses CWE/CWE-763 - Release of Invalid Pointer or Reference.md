---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-763"
status: "Incomplete"
---
# CWE-763: Release of Invalid Pointer or Reference

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product attempts to return a memory resource to the system, but it calls the wrong release function or calls the appropriate release function incorrectly.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Only call matching memory management functions. Do not mix and match routines. For example, when you allocate a buffer with malloc(), dispose of the original pointer with free().
- **Implementation:** When programming in C++, consider using smart pointers provided by the boost library to help correctly and consistently manage memory.
- **Architecture and Design:** Use a language that provides abstractions for memory allocation and deallocation.

## Related weaknesses

- CWE-404 (ChildOf)
- CWE-404 (ChildOf)
- CWE-404 (ChildOf)

## Source

- [CWE-763 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/763.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
