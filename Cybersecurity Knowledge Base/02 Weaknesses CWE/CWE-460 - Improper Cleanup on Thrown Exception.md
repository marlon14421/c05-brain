---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-460"
status: "Draft"
---
# CWE-460: Improper Cleanup on Thrown Exception

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Java, C#

## Description

The product does not clean up its state or incorrectly cleans up its state when an exception is thrown, leading to unexpected state or control flow.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If one breaks from a loop or function by throwing an exception, make sure that cleanup happens or that you should exit the program. Use throwing exceptions sparsely.

## Related weaknesses

- CWE-459 (ChildOf)
- CWE-755 (ChildOf)

## Source

- [CWE-460 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/460.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
