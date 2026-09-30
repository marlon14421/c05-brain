---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1298"
status: "Draft"
---
# CWE-1298: Hardware Logic Contains Race Conditions

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Verilog, VHDL, System on Chip

## Description

A race condition in the hardware logic results in undermining security guarantees of the system.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Adopting design practices that encourage designers to recognize and eliminate race conditions, such as Karnaugh maps, could result in the decrease in occurrences of race conditions.
- **Implementation:** Logic redundancy can be implemented along security critical paths to prevent race conditions. To avoid metastability, it is a good practice in general to default to a secure state in which access is not given to untrusted agents.

## Related weaknesses

- CWE-362 (ChildOf)

## Source

- [CWE-1298 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1298.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
