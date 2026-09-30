---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-495"
status: "Draft"
---
# CWE-495: Private Data Structure Returned From A Public Method

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Object-Oriented, C, C++, Java, C#

## Description

The product has a method that is declared public, but returns a reference to a private data structure, which could then be modified in unexpected ways.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Declare the method private.
- **Implementation:** Clone the member data and keep an unmodified version of the data private to the object.
- **Implementation:** Use public setter methods that govern how a private member can be modified.

## Related weaknesses

- CWE-664 (ChildOf)

## Source

- [CWE-495 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/495.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
