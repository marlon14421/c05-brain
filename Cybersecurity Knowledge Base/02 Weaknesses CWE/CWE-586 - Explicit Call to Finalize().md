---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-586"
status: "Draft"
---
# CWE-586: Explicit Call to Finalize()

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product makes an explicit call to the finalize() method from outside the finalizer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not make explicit calls to finalize().

## Related weaknesses

- CWE-1076 (ChildOf)

## Source

- [CWE-586 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/586.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
