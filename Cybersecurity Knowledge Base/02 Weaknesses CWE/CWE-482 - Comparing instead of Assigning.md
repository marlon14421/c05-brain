---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-482"
status: "Draft"
---
# CWE-482: Comparing instead of Assigning

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The code uses an operator for comparison when the intention was to perform an assignment.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** Many IDEs and static analysis products will detect this problem.

## Related weaknesses

- CWE-480 (ChildOf)

## Source

- [CWE-482 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/482.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
