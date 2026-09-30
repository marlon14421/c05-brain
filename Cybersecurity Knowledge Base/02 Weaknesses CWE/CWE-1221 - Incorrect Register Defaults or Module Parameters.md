---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1221"
status: "Incomplete"
---
# CWE-1221: Incorrect Register Defaults or Module Parameters

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Verilog, VHDL, Not Technology-Specific

## Description

Hardware description language code incorrectly defines register defaults or hardware Intellectual Property (IP) parameters to insecure values.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** During hardware design, all the system parameters and register defaults must be reviewed to identify security sensitive settings.
- **Implementation:** The default values of these security sensitive settings need to be defined as part of the design review phase.

## Related weaknesses

- CWE-1419 (ChildOf)

## Source

- [CWE-1221 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1221.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
