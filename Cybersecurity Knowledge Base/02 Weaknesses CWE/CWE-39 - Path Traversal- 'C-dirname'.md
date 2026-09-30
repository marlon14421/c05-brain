---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-39"
status: "Draft"
---
# CWE-39: Path Traversal: 'C:dirname'

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product accepts input that contains a drive letter or Windows volume letter ('C:dirname') that potentially redirects access to an unintended location or arbitrary file.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.

## Related weaknesses

- CWE-36 (ChildOf)

## Source

- [CWE-39 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/39.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
