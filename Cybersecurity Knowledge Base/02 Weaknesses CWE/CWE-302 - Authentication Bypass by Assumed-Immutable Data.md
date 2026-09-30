---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-302"
status: "Incomplete"
---
# CWE-302: Authentication Bypass by Assumed-Immutable Data

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

The authentication scheme or implementation uses key data elements that are assumed to be immutable, but can be controlled or modified by the attacker.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Implement proper protection for immutable data (e.g. environment variable, hidden form fields, etc.)

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-807 (ChildOf)

## Source

- [CWE-302 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/302.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
