---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-591"
status: "Draft"
---
# CWE-591: Sensitive Data Storage in Improperly Locked Memory

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product stores sensitive data in memory that is not locked, or that has been incorrectly locked, which might cause the memory to be written to swap files on disk by the virtual memory manager. This can make the data more accessible to external actors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Identify data that needs to be protected from swapping and choose platform-appropriate protection mechanisms.
- **Implementation:** Check return values to ensure locking operations are successful.

## Related weaknesses

- CWE-413 (ChildOf)

## Source

- [CWE-591 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/591.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
