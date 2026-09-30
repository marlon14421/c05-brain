---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-180"
status: "Draft"
---
# CWE-180: Incorrect Behavior Order: Validate Before Canonicalize

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product validates input before it is canonicalized, which prevents the product from detecting data that becomes invalid after the canonicalization step.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.

## Related weaknesses

- CWE-179 (ChildOf)

## Source

- [CWE-180 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/180.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
