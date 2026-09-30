---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-662"
status: "Draft"
---
# CWE-662: Improper Synchronization

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product utilizes multiple threads, processes, components, or systems to allow temporary access to a shared resource that can only be exclusive to one process at a time, but it does not properly synchronize these actions, which might cause simultaneous accesses of this resource by multiple threads or processes.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use industry standard APIs to synchronize your code.

## Related weaknesses

- CWE-664 (ChildOf)
- CWE-691 (ChildOf)
- CWE-362 (CanPrecede)

## Source

- [CWE-662 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/662.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
