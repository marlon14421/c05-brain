---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-489"
status: "Draft"
---
# CWE-489: Active Debug Code

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, ICS/OT

## Description

The product is released with debugging code still enabled or active.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Build and Compilation:** Remove debug code before deploying the application.

## Related weaknesses

- CWE-710 (ChildOf)
- CWE-215 (CanPrecede)

## Source

- [CWE-489 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/489.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
