---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-415"
status: "Draft"
---
# CWE-415: Double Free

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product calls free() twice on the same memory address.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Choose a language that provides automatic memory management.
- **Implementation:** Ensure that each allocation is freed only once. After freeing a chunk, set the pointer to NULL to ensure the pointer cannot be freed again. In complicated error conditions, be sure that clean-up routines respect the state of allocation properly. If the language is object oriented, ensure that object destructors delete each chunk of memory only once.
- **Implementation:** Use a static analysis tool to find double free instances.

## Related weaknesses

- CWE-825 (ChildOf)
- CWE-1341 (ChildOf)
- CWE-672 (ChildOf)
- CWE-672 (ChildOf)
- CWE-672 (ChildOf)
- CWE-666 (ChildOf)
- CWE-416 (PeerOf)
- CWE-123 (PeerOf)

## Source

- [CWE-415 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/415.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
