---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-562"
status: "Draft"
---
# CWE-562: Return of Stack Variable Address

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

A function returns the address of a stack variable, which will cause unintended program behavior, typically in the form of a crash.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Fix the code so that it does not return a stack address.

## Related weaknesses

- CWE-758 (ChildOf)
- CWE-672 (CanPrecede)
- CWE-825 (CanPrecede)

## Source

- [CWE-562 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/562.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
