---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-342"
status: "Draft"
---
# CWE-342: Predictable Exact Value from Previous Values

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

An exact value or random number can be precisely predicted by observing previous values.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Mitigation:** Increase the entropy used to seed a PRNG.
- **Architecture and Design:** Use products or modules that conform to FIPS 140-2 [REF-267] to avoid obvious entropy problems. Consult FIPS 140-2 Annex C ("Approved Random Number Generators").
- **Implementation:** Use a PRNG that periodically re-seeds itself using input from high-quality sources, such as hardware devices with high entropy. However, do not re-seed too frequently, or else the entropy source might block.

## Related weaknesses

- CWE-340 (ChildOf)

## Source

- [CWE-342 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/342.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
