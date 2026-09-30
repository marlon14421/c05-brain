---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-456"
status: "Draft"
---
# CWE-456: Missing Initialization of a Variable

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not initialize critical variables, which causes the execution environment to use unexpected values.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that critical variables are initialized before first use [REF-1485].
- **Requirements:** Choose a language that is not susceptible to these issues.

## Related weaknesses

- CWE-909 (ChildOf)
- CWE-665 (ChildOf)
- CWE-665 (ChildOf)
- CWE-89 (CanPrecede)
- CWE-120 (CanPrecede)
- CWE-98 (CanPrecede)
- CWE-457 (CanPrecede)

## Source

- [CWE-456 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/456.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
