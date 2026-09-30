---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-547"
status: "Draft"
---
# CWE-547: Use of Hard-coded, Security-relevant Constants

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses hard-coded constants instead of symbolic names for security-critical values, which increases the likelihood of mistakes during code maintenance or security policy change.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Avoid using hard-coded constants. Configuration files offer a more flexible solution.

## Related weaknesses

- CWE-1078 (ChildOf)

## Source

- [CWE-547 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/547.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
