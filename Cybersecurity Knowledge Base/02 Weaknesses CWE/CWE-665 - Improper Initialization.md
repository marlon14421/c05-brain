---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-665"
status: "Draft"
---
# CWE-665: Improper Initialization

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not initialize or incorrectly initializes a resource, which might leave the resource in an unexpected state when it is accessed or used.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Identify all variables and data stores that receive information from external sources, and apply input validation to make sure that they are only initialized to expected values.
- **Implementation:** Explicitly initialize all your variables and other data stores, either during declaration or just before the first usage.
- **Implementation:** Pay close attention to complex conditionals that affect initialization, since some conditions might not perform the initialization.
- **Implementation:** Avoid race conditions (CWE-362) during initialization routines.
- **Build and Compilation:** Run or compile your product with settings that generate warnings about uninitialized variables or data.

## Related weaknesses

- CWE-664 (ChildOf)

## Source

- [CWE-665 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/665.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
