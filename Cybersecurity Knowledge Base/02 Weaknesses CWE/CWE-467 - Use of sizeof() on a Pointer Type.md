---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-467"
status: "Draft"
---
# CWE-467: Use of sizeof() on a Pointer Type

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The code calls sizeof() on a pointer type, which can be an incorrect calculation if the programmer intended to determine the size of the data that is being pointed to.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use expressions such as "sizeof(*pointer)" instead of "sizeof(pointer)", unless you intend to run sizeof() on a pointer type to gain some platform independence or if you are allocating a variable on the stack.

## Related weaknesses

- CWE-131 (ChildOf)

## Source

- [CWE-467 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/467.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
