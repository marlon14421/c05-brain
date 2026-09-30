---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-567"
status: "Draft"
---
# CWE-567: Unsynchronized Access to Shared Data in a Multithreaded Context

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product does not properly synchronize shared data, such as static variables across threads, which can lead to undefined behavior and unpredictable data changes.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Remove the use of static variables used between servlets. If this cannot be avoided, use synchronized access for these variables.

## Related weaknesses

- CWE-820 (ChildOf)
- CWE-662 (ChildOf)
- CWE-662 (ChildOf)
- CWE-488 (CanPrecede)

## Source

- [CWE-567 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/567.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
