---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1241"
status: "Draft"
---
# CWE-1241: Use of Predictable Algorithm in Random Number Generator

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** System on Chip

## Description

The device uses an algorithm that is predictable and generates a pseudo-random number.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** It is highly recommended to use a true random number generator (TRNG) to ensure the security of encryption schemes. Hardware-based TRNGs generate unpredictable, unbiased, and independent random numbers because they employ physical phenomena, e.g., electrical noise, as sources to generate random numbers.
- **Implementation:** It is highly recommended to use a true random number generator (TRNG) to ensure the security of encryption schemes. Hardware-based TRNGs generate unpredictable, unbiased, and independent random numbers because they employ physical phenomena, e.g., electrical noise, as sources to generate random numbers.

## Related weaknesses

- CWE-330 (ChildOf)

## Source

- [CWE-1241 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1241.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
