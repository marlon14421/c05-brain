---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1223"
status: "Incomplete"
---
# CWE-1223: Race Condition for Write-Once Attributes

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Verilog, VHDL, System on Chip

## Description

A write-once register in hardware design is programmable by an untrusted software component earlier than the trusted software component, resulting in a race condition issue.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** During hardware design, all register write-once or sticky fields must be evaluated for proper configuration.

## Related weaknesses

- CWE-362 (ChildOf)

## Source

- [CWE-1223 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1223.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
