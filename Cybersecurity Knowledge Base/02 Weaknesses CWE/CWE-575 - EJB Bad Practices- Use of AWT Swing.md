---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-575"
status: "Draft"
---
# CWE-575: EJB Bad Practices: Use of AWT Swing

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product violates the Enterprise JavaBeans (EJB) specification by using AWT/Swing.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not use AWT/Swing when writing EJBs.

## Related weaknesses

- CWE-695 (ChildOf)

## Source

- [CWE-575 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/575.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
