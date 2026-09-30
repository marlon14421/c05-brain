---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-708"
status: "Incomplete"
---
# CWE-708: Incorrect Ownership Assignment

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product assigns an owner to a resource, but the owner is outside of the intended control sphere.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Policy:** Periodically review the privileges and their owners.

## Related weaknesses

- CWE-282 (ChildOf)
- CWE-345 (CanAlsoBe)

## Source

- [CWE-708 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/708.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
