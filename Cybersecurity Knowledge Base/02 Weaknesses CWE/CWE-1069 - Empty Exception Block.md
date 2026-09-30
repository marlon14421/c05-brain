---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1069"
status: "Incomplete"
---
# CWE-1069: Empty Exception Block

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

An invokable code block contains an exception handling block that does not contain any code, i.e. is empty.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** For every exception block add code that handles the specific exception in the way intended by the application.

## Related weaknesses

- CWE-1071 (ChildOf)

## Source

- [CWE-1069 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1069.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
