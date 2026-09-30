---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-783"
status: "Draft"
---
# CWE-783: Operator Precedence Logic Error

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Not Language-Specific

## Description

The product uses an expression in which operator precedence causes incorrect logic to be used.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Regularly wrap sub-expressions in parentheses, especially in security-critical code.

## Related weaknesses

- CWE-670 (ChildOf)

## Source

- [CWE-783 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/783.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
