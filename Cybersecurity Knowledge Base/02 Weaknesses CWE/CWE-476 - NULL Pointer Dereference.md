---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-476"
status: "Stable"
---
# CWE-476: NULL Pointer Dereference

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** C, C++, Java, C#, Go

## Description

The product dereferences a pointer that it expects to be valid but is NULL.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** For any pointers that could have been modified or provided from a function that can return NULL, check the pointer for NULL before use. When working with a multithreaded or otherwise asynchronous environment, ensure that proper locking APIs are used to lock before the check, and unlock when it has finished [REF-1484].
- **Requirements:** Select a programming language that is not susceptible to these issues.
- **Implementation:** Check the results of all functions that return a value and verify that the value is non-null before acting upon it.
- **Architecture and Design:** Identify all variables and data stores that receive information from external sources, and apply input validation to make sure that they are only initialized to expected values.
- **Implementation:** Explicitly initialize all variables and other data stores, either during declaration or just before the first usage.

## Related weaknesses

- CWE-710 (ChildOf)
- CWE-754 (ChildOf)
- CWE-754 (ChildOf)

## Source

- [CWE-476 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/476.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
