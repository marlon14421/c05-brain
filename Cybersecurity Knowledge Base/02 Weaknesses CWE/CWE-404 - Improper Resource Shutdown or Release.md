---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-404"
status: "Draft"
---
# CWE-404: Improper Resource Shutdown or Release

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not release or incorrectly releases a resource before it is made available for re-use.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** It is good practice to be responsible for freeing all resources you allocate and to be consistent with how and where you free memory in a function. If you allocate memory that you intend to free upon completion of the function, you must be sure to free the memory at all exit points for that function including error conditions.
- **Implementation:** Memory should be allocated/freed using matching functions such as malloc/free, new/delete, and new[]/delete[].
- **Implementation:** When releasing a complex object or structure, ensure that you properly dispose of all of its member components, not just the object itself.

## Related weaknesses

- CWE-664 (ChildOf)
- CWE-405 (PeerOf)
- CWE-619 (CanPrecede)

## Source

- [CWE-404 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/404.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
