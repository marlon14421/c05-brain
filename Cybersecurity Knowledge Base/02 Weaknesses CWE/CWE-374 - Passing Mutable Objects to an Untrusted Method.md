---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-374"
status: "Draft"
---
# CWE-374: Passing Mutable Objects to an Untrusted Method

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Object-Oriented, C, C++, Java, C#

## Description

The product sends non-cloned mutable data as an argument to a method or function.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Pass in data which should not be altered as constant or immutable.
- **Implementation:** Clone all mutable data before passing it into an external function . This is the preferred mitigation. This way, regardless of what changes are made to the data, a valid copy is retained for use by the class.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-374 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/374.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
