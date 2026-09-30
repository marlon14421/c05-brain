---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-681"
status: "Draft"
---
# CWE-681: Incorrect Conversion between Numeric Types

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, Not Language-Specific, Not Technology-Specific

## Description

When converting from one data type to another, such as long to integer, data can be omitted or translated in a way that produces unexpected values. If the resulting values are used in a sensitive context, then dangerous behaviors may occur.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Avoid making conversion between numeric types. Always check for the allowed ranges.

## Related weaknesses

- CWE-704 (ChildOf)
- CWE-704 (ChildOf)
- CWE-682 (CanPrecede)

## Source

- [CWE-681 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/681.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
