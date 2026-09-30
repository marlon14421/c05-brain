---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-543"
status: "Incomplete"
---
# CWE-543: Use of Singleton Pattern Without Synchronization in a Multithreaded Context

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, C++

## Description

The product uses the singleton pattern when creating a resource within a multithreaded environment.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use the Thread-Specific Storage Pattern. See References.
- **Implementation:** Do not use member fields to store information in the Servlet. In multithreading environments, storing user data in Servlet member fields introduces a data access race condition.
- **Implementation:** Avoid using the double-checked locking pattern in language versions that cannot guarantee thread safety. This pattern may be used to avoid the overhead of a synchronized call, but in certain versions of Java (for example), this has been shown to be unsafe because it still introduces a race condition (CWE-209).

## Related weaknesses

- CWE-820 (ChildOf)
- CWE-662 (ChildOf)
- CWE-662 (ChildOf)

## Source

- [CWE-543 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/543.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
