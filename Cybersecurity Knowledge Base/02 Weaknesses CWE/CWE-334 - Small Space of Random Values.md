---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-334"
status: "Draft"
---
# CWE-334: Small Space of Random Values

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The number of possible random values is smaller than needed by the product, making it more susceptible to brute force attacks.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use products or modules that conform to FIPS 140-2 [REF-267] to avoid obvious entropy problems. Consult FIPS 140-2 Annex C ("Approved Random Number Generators").

## Related weaknesses

- CWE-330 (ChildOf)

## Source

- [CWE-334 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/334.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
