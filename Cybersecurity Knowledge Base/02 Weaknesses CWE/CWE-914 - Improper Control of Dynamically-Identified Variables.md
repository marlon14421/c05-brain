---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-914"
status: "Incomplete"
---
# CWE-914: Improper Control of Dynamically-Identified Variables

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Interpreted

## Description

The product does not properly restrict reading from or writing to dynamically-identified variables.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** For any externally-influenced input, check the input against an allowlist of internal program variables that are allowed to be modified.
- **Implementation:** Refactor the code so that internal program variables do not need to be dynamically identified.

## Related weaknesses

- CWE-99 (ChildOf)
- CWE-913 (ChildOf)

## Source

- [CWE-914 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/914.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
