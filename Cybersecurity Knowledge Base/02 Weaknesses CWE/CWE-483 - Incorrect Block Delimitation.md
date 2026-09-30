---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-483"
status: "Draft"
---
# CWE-483: Incorrect Block Delimitation

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The code does not explicitly delimit a block that is intended to contain 2 or more statements, creating a logic error.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Always use explicit block delimitation and use static-analysis technologies to enforce this practice.

## Related weaknesses

- CWE-670 (ChildOf)

## Source

- [CWE-483 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/483.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
