---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-338"
status: "Draft"
---
# CWE-338: Use of Cryptographically Weak Pseudo-Random Number Generator (PRNG)

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product uses a Pseudo-Random Number Generator (PRNG) in a security context, but the PRNG's algorithm is not cryptographically strong.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use functions or hardware which use a hardware-based random number generation for all crypto. This is the recommended solution. Use CyptGenRandom on Windows, or hw_rand() on Linux.

## Related weaknesses

- CWE-330 (ChildOf)
- CWE-330 (ChildOf)

## Source

- [CWE-338 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/338.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
