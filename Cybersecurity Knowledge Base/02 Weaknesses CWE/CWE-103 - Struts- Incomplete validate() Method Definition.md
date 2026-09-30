---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-103"
status: "Draft"
---
# CWE-103: Struts: Incomplete validate() Method Definition

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product has a validator form that either does not define a validate() method, or defines a validate() method but does not call super.validate().

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Implement the validate() method and call super.validate() within that method.

## Related weaknesses

- CWE-573 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-103 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/103.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
