---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-524"
status: "Incomplete"
---
# CWE-524: Use of Cache Containing Sensitive Information

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The code uses a cache that contains sensitive information, but the cache can be read by an actor outside of the intended control sphere.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Protect information stored in cache.
- **Architecture and Design:** Do not store unnecessarily sensitive information in the cache.
- **Architecture and Design:** Consider using encryption in the cache.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-524 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/524.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
