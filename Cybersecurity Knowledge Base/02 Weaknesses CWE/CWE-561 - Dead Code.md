---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-561"
status: "Draft"
---
# CWE-561: Dead Code

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product contains dead code, which can never be executed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Remove dead code before deploying the application.

## Related weaknesses

- CWE-1164 (ChildOf)

## Source

- [CWE-561 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/561.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
