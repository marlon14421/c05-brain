---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-622"
status: "Draft"
---
# CWE-622: Improper Validation of Function Hook Arguments

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product adds hooks to user-accessible API functions, but it does not properly validate the arguments. This could lead to resultant vulnerabilities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that all arguments are verified, as defined by the API you are protecting.
- **Architecture and Design:** Drop privileges before invoking such functions, if possible.

## Related weaknesses

- CWE-20 (ChildOf)

## Source

- [CWE-622 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/622.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
