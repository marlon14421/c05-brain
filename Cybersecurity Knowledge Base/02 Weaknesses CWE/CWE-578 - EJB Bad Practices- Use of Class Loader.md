---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-578"
status: "Draft"
---
# CWE-578: EJB Bad Practices: Use of Class Loader

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product violates the Enterprise JavaBeans (EJB) specification by using the class loader.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not use the Class Loader when writing EJBs.

## Related weaknesses

- CWE-573 (ChildOf)

## Source

- [CWE-578 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/578.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
