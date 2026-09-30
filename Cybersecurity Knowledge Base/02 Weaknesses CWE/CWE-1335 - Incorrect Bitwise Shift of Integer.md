---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1335"
status: "Draft"
---
# CWE-1335: Incorrect Bitwise Shift of Integer

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, C#, Java, JavaScript, Not OS-Specific, Not Technology-Specific

## Description

An integer value is specified to be shifted by a negative amount or an amount greater than or equal to the number of bits contained in the value causing an unexpected or indeterminate result.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Implicitly or explicitly add checks and mitigation for negative or over-shift values.

## Related weaknesses

- CWE-682 (ChildOf)

## Source

- [CWE-1335 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1335.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
