---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1420"
status: "Incomplete"
---
# CWE-1420: Exposure of Sensitive Information during Transient Execution

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

A processor event or prediction may allow incorrect operations (or correct operations with incorrect data) to execute transiently, potentially exposing data over a covert channel.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The hardware designer can attempt to prevent transient execution from causing observable discrepancies in specific covert channels.

## Related weaknesses

- CWE-669 (ChildOf)

## Source

- [CWE-1420 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1420.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
