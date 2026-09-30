---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-913"
status: "Incomplete"
---
# CWE-913: Improper Control of Dynamically-Managed Code Resources

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Interpreted

## Description

The product does not properly restrict reading from or writing to dynamically-managed code resources such as variables, objects, classes, attributes, functions, or executable instructions or statements.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** For any externally-influenced input, check the input against an allowlist of acceptable values.
- **Implementation:** Refactor the code so that it does not need to be dynamically managed.

## Related weaknesses

- CWE-664 (ChildOf)

## Source

- [CWE-913 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/913.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
