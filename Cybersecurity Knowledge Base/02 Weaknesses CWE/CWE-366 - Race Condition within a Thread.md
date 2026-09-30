---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-366"
status: "Draft"
---
# CWE-366: Race Condition within a Thread

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Java, C#, Not Technology-Specific

## Description

If two threads of execution use a resource simultaneously, there exists the possibility that resources may be used while invalid, in turn making the state of execution undefined.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use locking functionality. This is the recommended solution. Implement some form of locking mechanism around code which alters or reads persistent data in a multithreaded environment.
- **Architecture and Design:** Create resource-locking validation checks. If no inherent locking mechanisms exist, use flags and signals to enforce your own blocking scheme when resources are being used by other threads of execution.

## Related weaknesses

- CWE-362 (ChildOf)
- CWE-662 (ChildOf)
- CWE-662 (ChildOf)

## Source

- [CWE-366 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/366.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
