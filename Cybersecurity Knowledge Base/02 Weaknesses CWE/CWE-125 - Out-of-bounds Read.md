---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-125"
status: "Draft"
---
# CWE-125: Out-of-bounds Read

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++, ICS/OT

## Description

The product reads data past the end, or before the beginning, of the intended buffer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a language that provides appropriate memory abstractions.

## Related weaknesses

- CWE-119 (ChildOf)
- CWE-119 (ChildOf)
- CWE-119 (ChildOf)
- CWE-119 (ChildOf)

## Source

- [CWE-125 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/125.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
