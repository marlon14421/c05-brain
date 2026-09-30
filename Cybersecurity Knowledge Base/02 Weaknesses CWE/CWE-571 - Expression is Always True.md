---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-571"
status: "Draft"
---
# CWE-571: Expression is Always True

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product contains an expression that will always evaluate to true.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Consider refactoring the code, or determine if the code is not including a condition that could cause the expression to become false.

## Related weaknesses

- CWE-710 (ChildOf)
- CWE-561 (CanPrecede)

## Source

- [CWE-571 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/571.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
