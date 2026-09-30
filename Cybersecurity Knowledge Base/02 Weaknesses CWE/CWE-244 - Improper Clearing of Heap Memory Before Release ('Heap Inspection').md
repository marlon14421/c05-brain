---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-244"
status: "Draft"
---
# CWE-244: Improper Clearing of Heap Memory Before Release ('Heap Inspection')

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

Using realloc() to resize buffers that store sensitive information can leave the sensitive information exposed to attack, because it is not removed from memory.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-226 (ChildOf)
- CWE-669 (CanPrecede)

## Source

- [CWE-244 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/244.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
