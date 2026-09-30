---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-341"
status: "Draft"
---
# CWE-341: Predictable from Observable State

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A number or object is predictable based on observations that the attacker can make about the state of the system or network, such as time, process ID, etc.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Increase the entropy used to seed a PRNG.
- **Architecture and Design:** Use products or modules that conform to FIPS 140-2 [REF-267] to avoid obvious entropy problems. Consult FIPS 140-2 Annex C ("Approved Random Number Generators").
- **Implementation:** Use a PRNG that periodically re-seeds itself using input from high-quality sources, such as hardware devices with high entropy. However, do not re-seed too frequently, or else the entropy source might block.

## Related weaknesses

- CWE-340 (ChildOf)

## Source

- [CWE-341 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/341.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
