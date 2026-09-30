---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-469"
status: "Draft"
---
# CWE-469: Use of Pointer Subtraction to Determine Size

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The product subtracts one pointer from another in order to determine size, but this calculation can be incorrect if the pointers do not exist in the same memory chunk.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Save an index variable. This is the recommended solution. Rather than subtract pointers from one another, use an index variable of the same size as the pointers in question. Use this variable to "walk" from one pointer to the other and calculate the difference. Always validate this number.

## Related weaknesses

- CWE-682 (ChildOf)

## Source

- [CWE-469 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/469.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
