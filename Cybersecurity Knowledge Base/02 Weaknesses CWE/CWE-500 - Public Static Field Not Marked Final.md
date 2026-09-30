---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-500"
status: "Draft"
---
# CWE-500: Public Static Field Not Marked Final

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C++, Java

## Description

An object contains a public static field that is not marked final, which might allow it to be modified in unexpected ways.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Clearly identify the scope for all critical data elements, including whether they should be regarded as static.

## Related weaknesses

- CWE-493 (ChildOf)

## Source

- [CWE-500 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/500.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
