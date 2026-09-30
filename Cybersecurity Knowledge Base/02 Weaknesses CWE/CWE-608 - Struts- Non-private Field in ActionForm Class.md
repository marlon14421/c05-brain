---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-608"
status: "Draft"
---
# CWE-608: Struts: Non-private Field in ActionForm Class

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

An ActionForm class contains a field that has not been declared private, which can be accessed without using a setter or getter.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Make all fields private. Use getter to get the value of the field. Setter should be used only by the framework; setting an action form field from other actions is bad practice and should be avoided.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-608 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/608.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
