---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-688"
status: "Draft"
---
# CWE-688: Function Call With Incorrect Variable or Reference as Argument

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, Perl

## Description

The product calls a function, procedure, or routine, but the caller specifies the wrong variable or reference as one of the arguments, which may lead to undefined behavior and resultant weaknesses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** Because this function call often produces incorrect behavior it will usually be detected during testing or normal operation of the product. During testing exercise all possible control paths will typically expose this weakness except in rare cases when the incorrect function call accidentally produces the correct results or if the provided argument type is very similar to the expected argument type.

## Related weaknesses

- CWE-628 (ChildOf)

## Source

- [CWE-688 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/688.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
