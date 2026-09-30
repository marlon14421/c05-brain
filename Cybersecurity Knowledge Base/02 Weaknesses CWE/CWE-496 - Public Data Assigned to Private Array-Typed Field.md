---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-496"
status: "Incomplete"
---
# CWE-496: Public Data Assigned to Private Array-Typed Field

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Object-Oriented, C, C++, Java, C#

## Description

Assigning public data to a private array is equivalent to giving public access to the array.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not allow objects to modify private members of a class.

## Related weaknesses

- CWE-664 (ChildOf)

## Source

- [CWE-496 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/496.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
