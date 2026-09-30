---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-710"
status: "Incomplete"
---
# CWE-710: Improper Adherence to Coding Standards

**Abstraction:** Pillar  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product does not follow certain coding rules for development, which can lead to resultant weaknesses or increase the severity of the associated vulnerabilities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Policy:** Select and require coding standards. Ensure that they include security concerns.
- **Implementation:** Closely follow coding standards, possibly enforcing them upon checkin of the code into a source control system or with periodic analyses.

## Source

- [CWE-710 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/710.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
