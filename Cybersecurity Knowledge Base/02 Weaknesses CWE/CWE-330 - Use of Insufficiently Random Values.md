---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-330"
status: "Stable"
---
# CWE-330: Use of Insufficiently Random Values

**Abstraction:** Class  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product uses insufficiently random numbers or values in a security context that depends on unpredictable numbers.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Consider a PRNG that re-seeds itself as needed from high quality pseudo-random output sources, such as hardware devices.
- **Architecture and Design:** Use products or modules that conform to FIPS 140-2 [REF-267] to avoid obvious entropy problems. Consult FIPS 140-2 Annex C ("Approved Random Number Generators").

## Related weaknesses

- CWE-693 (ChildOf)
- CWE-804 (CanPrecede)

## Source

- [CWE-330 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/330.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
