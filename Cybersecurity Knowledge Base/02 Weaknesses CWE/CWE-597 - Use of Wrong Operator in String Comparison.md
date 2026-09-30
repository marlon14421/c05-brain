---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-597"
status: "Draft"
---
# CWE-597: Use of Wrong Operator in String Comparison

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Java, JavaScript, PHP

## Description

The product uses the wrong operator when comparing a string, such as using "==" when the .equals() method should be used instead.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Within Java, use .equals() to compare string values.

## Related weaknesses

- CWE-595 (ChildOf)
- CWE-595 (ChildOf)
- CWE-480 (ChildOf)

## Source

- [CWE-597 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/597.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
