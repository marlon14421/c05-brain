---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-412"
status: "Incomplete"
---
# CWE-412: Unrestricted Externally Accessible Lock

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product properly checks for the existence of a lock, but the lock can be externally controlled or influenced by an actor that is outside of the intended sphere of control.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use any access control that is offered by the functionality that is offering the lock.
- **Architecture and Design:** Use unpredictable names or identifiers for the locks. This might not always be possible or feasible.
- **Architecture and Design:** Consider modifying your code to use non-blocking synchronization methods.

## Related weaknesses

- CWE-667 (ChildOf)
- CWE-410 (CanAlsoBe)

## Source

- [CWE-412 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/412.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
