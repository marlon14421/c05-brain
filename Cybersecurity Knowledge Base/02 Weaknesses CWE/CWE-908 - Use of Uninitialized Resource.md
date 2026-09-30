---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-908"
status: "Incomplete"
---
# CWE-908: Use of Uninitialized Resource

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses or accesses a resource that has not been initialized.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Explicitly initialize the resource before use. If this is performed through an API function or standard procedure, follow all required steps.
- **Implementation:** Pay close attention to complex conditionals that affect initialization, since some branches might not perform the initialization.
- **Implementation:** Avoid race conditions (CWE-362) during initialization routines.
- **Build and Compilation:** Run or compile the product with settings that generate warnings about uninitialized variables or data.

## Related weaknesses

- CWE-665 (ChildOf)
- CWE-665 (ChildOf)

## Source

- [CWE-908 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/908.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
