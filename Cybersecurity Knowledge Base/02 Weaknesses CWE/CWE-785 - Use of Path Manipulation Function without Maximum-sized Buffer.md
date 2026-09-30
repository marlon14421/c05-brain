---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-785"
status: "Incomplete"
---
# CWE-785: Use of Path Manipulation Function without Maximum-sized Buffer

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

The product invokes a function for normalizing paths or file names, but it provides an output buffer that is smaller than the maximum possible size, such as PATH_MAX.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Always specify output buffers large enough to handle the maximum-size possible result from path manipulation functions.

## Related weaknesses

- CWE-676 (ChildOf)
- CWE-120 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-785 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/785.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
