---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-395"
status: "Draft"
---
# CWE-395: Use of NullPointerException Catch to Detect NULL Pointer Dereference

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

Catching NullPointerException should not be used as an alternative to programmatic checks to prevent dereferencing a null pointer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not extensively rely on catching exceptions (especially for validating user input) to handle errors. Handling exceptions can decrease the performance of an application.

## Related weaknesses

- CWE-705 (ChildOf)
- CWE-755 (ChildOf)

## Source

- [CWE-395 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/395.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
