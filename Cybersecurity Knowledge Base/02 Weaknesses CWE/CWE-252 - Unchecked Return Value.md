---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-252"
status: "Draft"
---
# CWE-252: Unchecked Return Value

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not check the return value from a method or function, which can prevent it from detecting unexpected states and conditions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Check the results of all functions that return a value and verify that the value is expected.
- **Implementation:** For any pointers that could have been modified or provided from a function that can return NULL, check the pointer for NULL before use. When working with a multithreaded or otherwise asynchronous environment, ensure that proper locking APIs are used to lock before the check, and unlock when it has finished [REF-1484].
- **Implementation:** Ensure that you account for all possible return values from the function.
- **Implementation:** When designing a function, make sure you return a value or throw an exception in case of an error.

## Related weaknesses

- CWE-754 (ChildOf)
- CWE-754 (ChildOf)
- CWE-476 (CanPrecede)

## Source

- [CWE-252 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/252.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
