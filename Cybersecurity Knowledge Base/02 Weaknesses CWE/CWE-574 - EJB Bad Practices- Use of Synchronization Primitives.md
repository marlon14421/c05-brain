---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-574"
status: "Draft"
---
# CWE-574: EJB Bad Practices: Use of Synchronization Primitives

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product violates the Enterprise JavaBeans (EJB) specification by using thread synchronization primitives.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not use Synchronization Primitives when writing EJBs.

## Related weaknesses

- CWE-695 (ChildOf)
- CWE-821 (ChildOf)

## Source

- [CWE-574 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/574.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
