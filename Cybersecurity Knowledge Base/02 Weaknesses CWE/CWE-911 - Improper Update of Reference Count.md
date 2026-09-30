---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-911"
status: "Incomplete"
---
# CWE-911: Improper Update of Reference Count

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++, Not Language-Specific

## Description

The product uses a reference count to manage a resource, but it does not update or incorrectly updates the reference count.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-664 (ChildOf)
- CWE-672 (CanPrecede)
- CWE-772 (CanPrecede)

## Source

- [CWE-911 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/911.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
