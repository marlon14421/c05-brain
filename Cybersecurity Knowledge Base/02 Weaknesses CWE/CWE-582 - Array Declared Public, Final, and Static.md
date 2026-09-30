---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-582"
status: "Draft"
---
# CWE-582: Array Declared Public, Final, and Static

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product declares an array public, final, and static, which is not sufficient to prevent the array's contents from being modified.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** In most situations the array should be made private.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-582 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/582.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
