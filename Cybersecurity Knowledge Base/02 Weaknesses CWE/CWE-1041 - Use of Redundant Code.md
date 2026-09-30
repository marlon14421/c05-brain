---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1041"
status: "Incomplete"
---
# CWE-1041: Use of Redundant Code

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product has multiple functions, methods, procedures, macros, etc. that contain the same code.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Merge common functionality into a single function and then call that function from across the entire code base.

## Related weaknesses

- CWE-710 (ChildOf)

## Source

- [CWE-1041 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1041.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
