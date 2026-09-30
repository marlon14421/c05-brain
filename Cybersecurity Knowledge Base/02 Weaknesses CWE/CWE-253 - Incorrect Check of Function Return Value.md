---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-253"
status: "Incomplete"
---
# CWE-253: Incorrect Check of Function Return Value

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product incorrectly checks a return value from a function, which prevents it from detecting errors or exceptional conditions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a language or compiler that uses exceptions and requires the catching of those exceptions.
- **Implementation:** Properly check all functions which return a value.
- **Implementation:** When designing any function make sure you return a value or throw an exception in case of an error.

## Related weaknesses

- CWE-573 (ChildOf)
- CWE-754 (ChildOf)

## Source

- [CWE-253 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/253.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
