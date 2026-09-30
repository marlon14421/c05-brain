---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-246"
status: "Draft"
---
# CWE-246: J2EE Bad Practices: Direct Use of Sockets

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The J2EE application directly uses sockets instead of using framework method calls.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use framework method calls instead of using sockets directly.

## Related weaknesses

- CWE-695 (ChildOf)

## Source

- [CWE-246 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/246.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
