---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-466"
status: "Draft"
---
# CWE-466: Return of Pointer Value Outside of Expected Range

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

A function can return a pointer to memory that is outside of the buffer that the pointer is expected to reference.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-119 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-466 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/466.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
