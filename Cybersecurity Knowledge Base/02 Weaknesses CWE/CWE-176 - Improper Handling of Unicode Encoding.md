---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-176"
status: "Draft"
---
# CWE-176: Improper Handling of Unicode Encoding

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product does not properly handle when an input contains Unicode encoding.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Avoid making decisions based on names of resources (e.g. files) if those resources can have alternate names.
- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.

## Related weaknesses

- CWE-172 (ChildOf)

## Source

- [CWE-176 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/176.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
