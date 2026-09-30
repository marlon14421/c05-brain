---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-183"
status: "Draft"
---
# CWE-183: Permissive List of Allowed Inputs

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product implements a protection mechanism that relies on a list of inputs (or properties of inputs) that are explicitly allowed by policy because the inputs are assumed to be safe, but the list is too permissive - that is, it allows an input that is unsafe, leading to resultant weaknesses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-697 (ChildOf)
- CWE-434 (CanPrecede)

## Source

- [CWE-183 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/183.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
