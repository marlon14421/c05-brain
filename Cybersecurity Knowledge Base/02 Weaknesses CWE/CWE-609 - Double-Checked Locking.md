---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-609"
status: "Draft"
---
# CWE-609: Double-Checked Locking

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product uses double-checked locking to access a resource without the overhead of explicit synchronization, but the locking is insufficient.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** While double-checked locking can be achieved in some languages, it is inherently flawed in Java before 1.5, and cannot be achieved without compromising platform independence. Before Java 1.5, only use of the synchronized keyword is known to work. Beginning in Java 1.5, use of the "volatile" keyword allows double-checked locking to work successfully, although there is some debate as to whether it achieves sufficient performance gains. See references.

## Related weaknesses

- CWE-667 (ChildOf)
- CWE-367 (CanPrecede)

## Source

- [CWE-609 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/609.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
