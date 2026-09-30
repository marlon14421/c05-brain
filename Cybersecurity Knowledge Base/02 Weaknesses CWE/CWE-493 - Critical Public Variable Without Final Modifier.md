---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-493"
status: "Draft"
---
# CWE-493: Critical Public Variable Without Final Modifier

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Object-Oriented, Java, C++

## Description

The product has a critical public variable that is not final, which allows the variable to be modified to contain unexpected values.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Declare all public fields as final when possible, especially if it is used to maintain internal state of an Applet or of classes used by an Applet. If a field must be public, then perform all appropriate sanity checks before accessing the field from your code.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-493 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/493.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
