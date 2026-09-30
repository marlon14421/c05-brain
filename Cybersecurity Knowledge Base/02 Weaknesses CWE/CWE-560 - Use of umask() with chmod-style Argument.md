---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-560"
status: "Draft"
---
# CWE-560: Use of umask() with chmod-style Argument

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C

## Description

The product calls umask() with an incorrect argument that is specified as if it is an argument to chmod().

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use umask() with the correct argument.

## Related weaknesses

- CWE-687 (ChildOf)

## Source

- [CWE-560 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/560.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
