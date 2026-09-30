---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-336"
status: "Draft"
---
# CWE-336: Same Seed in Pseudo-Random Number Generator (PRNG)

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A Pseudo-Random Number Generator (PRNG) uses the same seed each time the product is initialized.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not reuse PRNG seeds. Consider a PRNG that periodically re-seeds itself as needed from a high quality pseudo-random output, such as hardware devices.
- **Architecture and Design:** Use products or modules that conform to FIPS 140-2 [REF-267] to avoid obvious entropy problems, or use the more recent FIPS 140-3 [REF-1192] if possible.

## Related weaknesses

- CWE-335 (ChildOf)

## Source

- [CWE-336 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/336.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
