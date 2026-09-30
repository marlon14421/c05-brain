---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-135"
status: "Draft"
---
# CWE-135: Incorrect Calculation of Multi-Byte String Length

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The product does not correctly calculate the length of strings that can contain wide or multi-byte characters.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Always verify the length of the string unit character.
- **Implementation:** Use length computing functions (e.g. strlen, wcslen, etc.) appropriately with their equivalent type (e.g.: byte, wchar_t, etc.)

## Related weaknesses

- CWE-682 (ChildOf)

## Source

- [CWE-135 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/135.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
