---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1096"
status: "Incomplete"
---
# CWE-1096: Singleton Class Instance Creation without Proper Locking or Synchronization

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product implements a Singleton design pattern but does not use appropriate locking or other synchronization mechanism to ensure that the singleton class is only instantiated once.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-820 (ChildOf)
- CWE-662 (ChildOf)
- CWE-662 (ChildOf)

## Source

- [CWE-1096 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1096.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
