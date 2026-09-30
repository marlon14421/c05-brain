---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-484"
status: "Draft"
---
# CWE-484: Omitted Break Statement in Switch

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Java, C#, PHP, Not Language-Specific

## Description

The product omits a break statement within a switch or similar construct, causing code associated with multiple conditions to execute. This can cause problems when the programmer only intended to execute code associated with one condition.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Omitting a break statement so that one may fall through is often indistinguishable from an error, and therefore should be avoided. If you need to use fall-through capabilities, make sure that you have clearly documented this within the switch statement, and ensure that you have examined all the logical possibilities.
- **Implementation:** The functionality of omitting a break statement could be clarified with an if statement. This method is much safer.

## Related weaknesses

- CWE-710 (ChildOf)
- CWE-670 (ChildOf)

## Source

- [CWE-484 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/484.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
