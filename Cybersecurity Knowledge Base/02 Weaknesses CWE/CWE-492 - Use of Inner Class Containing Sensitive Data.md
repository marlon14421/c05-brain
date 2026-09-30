---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-492"
status: "Draft"
---
# CWE-492: Use of Inner Class Containing Sensitive Data

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

Inner classes are translated into classes that are accessible at package scope and may expose code that the programmer intended to keep private to attackers.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Using sealed classes protects object-oriented encapsulation paradigms and therefore protects code from being extended in unforeseen ways.
- **Implementation:** Inner Classes do not provide security. Warning: Never reduce the security of the object from an outer class, going to an inner class. If an outer class is final or private, ensure that its inner class is private as well.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-492 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/492.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
