---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-193"
status: "Draft"
---
# CWE-193: Off-by-one Error

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, Not Language-Specific

## Description

A product calculates or uses an incorrect maximum or minimum value that is 1 more, or 1 less, than the correct value.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When copying character arrays or using character manipulation methods, the correct size parameter must be used to account for the null terminator that needs to be added at the end of the array. Some examples of functions susceptible to this weakness in C include strcpy(), strncpy(), strcat(), strncat(), printf(), sprintf(), scanf() and sscanf().

## Related weaknesses

- CWE-682 (ChildOf)
- CWE-682 (ChildOf)
- CWE-617 (CanPrecede)
- CWE-170 (CanPrecede)
- CWE-119 (CanPrecede)

## Source

- [CWE-193 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/193.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
