---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-390"
status: "Draft"
---
# CWE-390: Detection of Error Condition Without Action

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product detects a specific error, but takes no actions to handle the error.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Properly handle each exception. This is the recommended solution. Ensure that all exceptions are handled in such a way that you can be sure of the state of your system at any given moment.
- **Implementation:** If a function returns an error, it is important to either fix the problem and try again, alert the user that an error has happened and let the program continue, or alert the user and close and cleanup the program.
- **Testing:** Subject the product to extensive testing to discover some of the possible instances of where/how errors or return values are not handled. Consider testing techniques such as ad hoc, equivalence partitioning, robustness and fault tolerance, mutation, and fuzzing.

## Related weaknesses

- CWE-755 (ChildOf)
- CWE-401 (CanPrecede)

## Source

- [CWE-390 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/390.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
