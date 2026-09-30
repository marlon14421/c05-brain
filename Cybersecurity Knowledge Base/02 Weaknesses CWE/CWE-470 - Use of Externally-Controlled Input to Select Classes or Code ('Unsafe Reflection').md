---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-470"
status: "Draft"
---
# CWE-470: Use of Externally-Controlled Input to Select Classes or Code ('Unsafe Reflection')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Java, PHP, Interpreted

## Description

The product uses external input with reflection to select which classes or code to use, but it does not sufficiently prevent the input from selecting improper classes or code.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Refactor your code to avoid using reflection.
- **Architecture and Design:** Do not use user-controlled inputs to select and load classes or code.
- **Implementation:** Apply strict input validation by using allowlists or indirect selection to ensure that the user is only selecting allowable classes or code.

## Related weaknesses

- CWE-913 (ChildOf)
- CWE-913 (ChildOf)
- CWE-610 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-470 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/470.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
