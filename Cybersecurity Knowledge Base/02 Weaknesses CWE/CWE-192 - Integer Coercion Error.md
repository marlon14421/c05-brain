---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-192"
status: "Incomplete"
---
# CWE-192: Integer Coercion Error

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++, Java, C#

## Description

Integer coercion refers to a set of flaws pertaining to the type casting, extension, or truncation of primitive data types.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** A language which throws exceptions on ambiguous data casts might be chosen.
- **Architecture and Design:** Design objects and program flow such that multiple or complex casts are unnecessary
- **Implementation:** Ensure that any data type casting that you must used is entirely understood in order to reduce the plausibility of error in use.

## Related weaknesses

- CWE-681 (ChildOf)

## Source

- [CWE-192 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/192.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
