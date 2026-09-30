---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-463"
status: "Incomplete"
---
# CWE-463: Deletion of Data Structure Sentinel

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

The accidental deletion of a data-structure sentinel can cause serious programming logic problems.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use an abstraction library to abstract away risky APIs. Not a complete solution.
- **Operation:** Use OS-level preventative functionality. Not a complete solution.

## Related weaknesses

- CWE-707 (ChildOf)
- CWE-464 (PeerOf)

## Source

- [CWE-463 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/463.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
