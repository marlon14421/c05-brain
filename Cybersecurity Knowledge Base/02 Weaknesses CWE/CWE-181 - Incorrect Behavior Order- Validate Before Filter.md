---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-181"
status: "Draft"
---
# CWE-181: Incorrect Behavior Order: Validate Before Filter

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product validates data before it has been filtered, which prevents the product from detecting data that becomes invalid after the filtering step.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being filtered.

## Related weaknesses

- CWE-179 (ChildOf)

## Source

- [CWE-181 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/181.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
