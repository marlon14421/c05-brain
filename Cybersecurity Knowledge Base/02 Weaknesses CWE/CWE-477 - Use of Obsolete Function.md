---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-477"
status: "Draft"
---
# CWE-477: Use of Obsolete Function

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The code uses deprecated or obsolete functions, which suggests that the code has not been actively reviewed or maintained.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Refer to the documentation for the obsolete function in order to determine why it is deprecated or obsolete and to learn about alternative ways to achieve the same functionality.
- **Requirements:** Consider seriously the security implications of using an obsolete function. Consider using alternate functions.

## Related weaknesses

- CWE-710 (ChildOf)

## Source

- [CWE-477 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/477.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
