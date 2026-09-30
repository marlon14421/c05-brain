---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-685"
status: "Draft"
---
# CWE-685: Function Call With Incorrect Number of Arguments

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, Perl

## Description

The product calls a function, procedure, or routine, but the caller specifies too many arguments, or too few arguments, which may lead to undefined behavior and resultant weaknesses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** Because this function call often produces incorrect behavior it will usually be detected during testing or normal operation of the product. During testing exercise all possible control paths will typically expose this weakness except in rare cases when the incorrect function call accidentally produces the correct results or if the provided argument type is very similar to the expected argument type.

## Related weaknesses

- CWE-628 (ChildOf)

## Source

- [CWE-685 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/685.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
