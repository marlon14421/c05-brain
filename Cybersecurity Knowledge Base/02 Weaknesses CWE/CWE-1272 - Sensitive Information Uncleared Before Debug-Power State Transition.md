---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1272"
status: "Stable"
---
# CWE-1272: Sensitive Information Uncleared Before Debug/Power State Transition

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** VHDL, Verilog, Hardware Description Language, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product performs a power or debug state transition, but it does not clear sensitive information that should no longer be accessible due to changes to information access restrictions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** During state transitions, information not needed in the next state should be removed before the transition to the next state.

## Related weaknesses

- CWE-226 (ChildOf)
- CWE-200 (CanPrecede)

## Source

- [CWE-1272 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1272.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
