---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-491"
status: "Draft"
---
# CWE-491: Public cloneable() Method Without Final ('Object Hijack')

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

A class has a cloneable() method that is not declared final, which allows an object to be created without calling the constructor. This can cause the object to be in an unexpected state.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Make the cloneable() method final.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-491 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/491.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
