---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-106"
status: "Draft"
---
# CWE-106: Struts: Plug-in Framework not in Use

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

When an application does not use an input validation framework such as the Struts Validator, there is a greater risk of introducing weaknesses related to insufficient input validation.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use an input validation framework such as Struts.
- **Architecture and Design:** Use an input validation framework such as Struts.

## Related weaknesses

- CWE-1173 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-106 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/106.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
