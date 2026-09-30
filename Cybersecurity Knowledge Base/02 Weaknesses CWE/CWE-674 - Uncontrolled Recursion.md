---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-674"
status: "Draft"
---
# CWE-674: Uncontrolled Recursion

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not properly control the amount of recursion that takes place, consuming excessive resources, such as allocated memory or the program stack.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that an end condition will be reached under all logic conditions. The end condition may include checking against the depth of recursion and exiting with an error if the recursion goes too deep. The complexity of the end condition contributes to the effectiveness of this action.
- **Implementation:** Increase the stack size.

## Related weaknesses

- CWE-834 (ChildOf)

## Source

- [CWE-674 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/674.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
