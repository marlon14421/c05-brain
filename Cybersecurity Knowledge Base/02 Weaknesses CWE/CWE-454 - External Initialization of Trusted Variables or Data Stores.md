---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-454"
status: "Draft"
---
# CWE-454: External Initialization of Trusted Variables or Data Stores

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** PHP, Not Language-Specific

## Description

The product initializes critical internal variables or data stores using inputs that can be modified by untrusted actors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** A product system should be reluctant to trust variables that have been initialized outside of its trust boundary. Ensure adequate checking (e.g. input validation) is performed when relying on input from outside a trust boundary.
- **Architecture and Design:** Avoid any external control of variables. If necessary, restrict the variables that can be modified using an allowlist, and use a different namespace or naming convention if possible.

## Related weaknesses

- CWE-1419 (ChildOf)
- CWE-456 (CanAlsoBe)

## Source

- [CWE-454 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/454.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
