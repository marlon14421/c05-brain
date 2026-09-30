---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-621"
status: "Incomplete"
---
# CWE-621: Variable Extraction Error

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** PHP

## Description

The product uses external input to determine the names of variables into which information is extracted, without verifying that the names of the specified variables are valid. This could cause the program to overwrite unintended variables.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use allowlists of variable names that can be extracted.
- **Implementation:** Consider refactoring your code to avoid extraction routines altogether.
- **Implementation:** In PHP, call extract() with options such as EXTR_SKIP and EXTR_PREFIX_ALL; call import_request_variables() with a prefix argument. Note that these capabilities are not present in all PHP versions.

## Related weaknesses

- CWE-914 (ChildOf)
- CWE-471 (CanPrecede)

## Source

- [CWE-621 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/621.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
