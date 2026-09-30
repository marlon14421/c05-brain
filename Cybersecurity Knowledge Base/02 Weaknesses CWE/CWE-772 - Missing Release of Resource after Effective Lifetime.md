---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-772"
status: "Draft"
---
# CWE-772: Missing Release of Resource after Effective Lifetime

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Mobile

## Description

The product does not release a resource after its effective lifetime has ended, i.e., after the resource is no longer needed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** It is good practice to be responsible for freeing all resources you allocate and to be consistent with how and where you free resources in a function. If you allocate resources that you intend to free upon completion of the function, you must be sure to free the resources at all exit points for that function including error conditions.

## Related weaknesses

- CWE-404 (ChildOf)
- CWE-404 (ChildOf)
- CWE-404 (ChildOf)
- CWE-404 (ChildOf)

## Source

- [CWE-772 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/772.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
