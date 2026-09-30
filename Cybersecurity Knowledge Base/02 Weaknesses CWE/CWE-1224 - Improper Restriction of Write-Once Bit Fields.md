---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1224"
status: "Incomplete"
---
# CWE-1224: Improper Restriction of Write-Once Bit Fields

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Verilog, VHDL, System on Chip

## Description

The hardware design control register "sticky bits" or write-once bit fields are improperly implemented, such that they can be reprogrammed by software.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** During hardware design, all register write-once or sticky fields must be evaluated for proper configuration.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1224 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1224.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
