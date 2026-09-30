---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-178"
status: "Incomplete"
---
# CWE-178: Improper Handling of Case Sensitivity

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Windows, macOS, Not Technology-Specific

## Description

The product does not properly account for differences in case sensitivity when accessing or determining the properties of a resource, leading to inconsistent results.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Avoid making decisions based on names of resources (e.g. files) if those resources can have alternate names.
- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.

## Related weaknesses

- CWE-706 (ChildOf)
- CWE-706 (ChildOf)
- CWE-433 (CanPrecede)
- CWE-289 (CanPrecede)

## Source

- [CWE-178 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/178.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
