---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1262"
status: "Stable"
---
# CWE-1262: Improper Access Control for Register Interface

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product uses memory-mapped I/O registers that act as an interface to hardware functionality from software, but there is improper access control to those registers.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Design proper policies for hardware register access from software.
- **Implementation:** Ensure that access control policies for register access are implemented in accordance with the specified design.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1262 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1262.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
