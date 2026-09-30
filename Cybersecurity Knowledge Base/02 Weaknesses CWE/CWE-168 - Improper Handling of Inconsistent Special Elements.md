---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-168"
status: "Draft"
---
# CWE-168: Improper Handling of Inconsistent Special Elements

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not properly handle input in which an inconsistency exists between two or more special characters or reserved words.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Mitigation:** Developers should anticipate that inconsistent special elements will be injected/manipulated in the input vectors of their product. Use an appropriate combination of denylists and allowlists to ensure only valid, expected and appropriate input is processed by the system.
- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.

## Related weaknesses

- CWE-159 (ChildOf)
- CWE-228 (ChildOf)

## Source

- [CWE-168 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/168.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
