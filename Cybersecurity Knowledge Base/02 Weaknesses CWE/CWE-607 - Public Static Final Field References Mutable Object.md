---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-607"
status: "Draft"
---
# CWE-607: Public Static Final Field References Mutable Object

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

A public or protected static final field references a mutable object, which allows the object to be changed by malicious code, or accidentally from another package.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Protect mutable objects by making them private. Restrict access to the getter and setter as well.

## Related weaknesses

- CWE-471 (ChildOf)

## Source

- [CWE-607 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/607.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
