---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-628"
status: "Draft"
---
# CWE-628: Function Call with Incorrectly Specified Arguments

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product calls a function, procedure, or routine with arguments that are not correctly specified, leading to always-incorrect behavior and resultant weaknesses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Build and Compilation:** Once found, these issues are easy to fix. Use code inspection tools and relevant compiler features to identify potential violations. Pay special attention to code that is not likely to be exercised heavily during QA.
- **Architecture and Design:** Make sure your API's are stable before you use them in production code.

## Related weaknesses

- CWE-573 (ChildOf)

## Source

- [CWE-628 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/628.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
