---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-478"
status: "Draft"
---
# CWE-478: Missing Default Case in Multiple Condition Expression

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Java, C#, Python, JavaScript

## Description

The code does not have a default case in an expression with multiple conditions, such as a switch statement.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that there are no cases unaccounted for when adjusting program flow or values based on the value of a given variable. In the case of switch style statements, the very simple act of creating a default case can, if done correctly, mitigate this situation. Often however, the default case is used simply to represent an assumed option, as opposed to working as a check for invalid input. This is poor practice and in some cases is as bad as omitting a default case entirely.

## Related weaknesses

- CWE-1023 (ChildOf)

## Source

- [CWE-478 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/478.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
