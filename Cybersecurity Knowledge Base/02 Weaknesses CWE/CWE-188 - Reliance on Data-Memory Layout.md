---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-188"
status: "Draft"
---
# CWE-188: Reliance on Data/Memory Layout

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, C, C++

## Description

The product makes invalid assumptions about how protocol data or memory is organized at a lower level, resulting in unintended program behavior.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** In flat address space situations, never allow computing memory addresses as offsets from another memory address.
- **Architecture and Design:** Fully specify protocol layout unambiguously, providing a structured grammar (e.g., a compilable yacc grammar).
- **Testing:** Testing: Test that the implementation properly handles each case in the protocol grammar.

## Related weaknesses

- CWE-1105 (ChildOf)
- CWE-435 (ChildOf)

## Source

- [CWE-188 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/188.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
