---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-563"
status: "Draft"
---
# CWE-563: Assignment to Variable without Use

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The variable's value is assigned but never used, making it a dead store.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Remove unused variables from the code.

## Related weaknesses

- CWE-1164 (ChildOf)

## Source

- [CWE-563 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/563.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
