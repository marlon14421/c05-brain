---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-273"
status: "Incomplete"
---
# CWE-273: Improper Check for Dropped Privileges

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product attempts to drop privileges but does not check or incorrectly checks to see if the drop succeeded.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Check the results of all functions that return a value and verify that the value is expected.
- **Implementation:** In Windows, make sure that the process token has the SeImpersonatePrivilege(Microsoft Server 2003). Code that relies on impersonation for security must ensure that the impersonation succeeded, i.e., that a proper privilege demotion happened.

## Related weaknesses

- CWE-754 (ChildOf)
- CWE-754 (ChildOf)
- CWE-271 (ChildOf)
- CWE-252 (PeerOf)

## Source

- [CWE-273 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/273.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
