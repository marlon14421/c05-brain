---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-385"
status: "Incomplete"
---
# CWE-385: Covert Timing Channel

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

Covert timing channels convey information by modulating some aspect of system behavior over time, so that the program receiving the information can observe system behavior and infer protected information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Whenever possible, specify implementation strategies that do not introduce time variances in operations.
- **Implementation:** Often one can artificially manipulate the time which operations take or -- when operations occur -- can remove information from the attacker.
- **Implementation:** It is reasonable to add artificial or random delays so that the amount of CPU time consumed is independent of the action being taken by the application.

## Related weaknesses

- CWE-514 (ChildOf)

## Source

- [CWE-385 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/385.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
