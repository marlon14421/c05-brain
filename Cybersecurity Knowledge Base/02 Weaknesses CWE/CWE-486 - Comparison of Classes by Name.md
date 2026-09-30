---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-486"
status: "Draft"
---
# CWE-486: Comparison of Classes by Name

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product compares classes by name, which can cause it to use the wrong class when multiple classes can have the same name.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use class equivalency to determine type. Rather than use the class name to determine if an object is of a given type, use the getClass() method, and == operator.

## Related weaknesses

- CWE-1025 (ChildOf)

## Source

- [CWE-486 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/486.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
