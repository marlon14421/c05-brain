---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-474"
status: "Draft"
---
# CWE-474: Use of Function with Inconsistent Implementations

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, PHP, Not Language-Specific

## Description

The code uses a function that has inconsistent implementations across operating systems and versions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not accept inconsistent behavior from the API specifications when the deviant behavior increase the risk level.

## Related weaknesses

- CWE-758 (ChildOf)

## Source

- [CWE-474 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/474.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
