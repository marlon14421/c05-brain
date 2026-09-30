---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-627"
status: "Incomplete"
---
# CWE-627: Dynamic Variable Evaluation

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** PHP, Perl

## Description

In a language where the user can influence the name of a variable at runtime, if the variable names are not controlled, an attacker can read or write to arbitrary variables, or access arbitrary functions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Refactor the code to avoid dynamic variable evaluation whenever possible.
- **Implementation:** Use only allowlists of acceptable variable or function names.
- **Implementation:** For function names, ensure that you are only calling functions that accept the proper number of arguments, to avoid unexpected null arguments.

## Related weaknesses

- CWE-914 (ChildOf)
- CWE-183 (PeerOf)

## Source

- [CWE-627 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/627.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
