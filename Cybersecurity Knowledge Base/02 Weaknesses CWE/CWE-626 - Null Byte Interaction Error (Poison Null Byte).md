---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-626"
status: "Draft"
---
# CWE-626: Null Byte Interaction Error (Poison Null Byte)

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** PHP, Perl, ASP.NET

## Description

The product does not properly handle null bytes or NUL characters when passing data between different representations or components.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Remove null bytes from all incoming strings.

## Related weaknesses

- CWE-147 (ChildOf)
- CWE-436 (ChildOf)

## Source

- [CWE-626 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/626.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
