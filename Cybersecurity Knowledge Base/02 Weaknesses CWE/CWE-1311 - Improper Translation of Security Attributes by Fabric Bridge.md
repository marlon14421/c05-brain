---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1311"
status: "Draft"
---
# CWE-1311: Improper Translation of Security Attributes by Fabric Bridge

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Verilog, VHDL, Not Technology-Specific

## Description

The bridge incorrectly translates security attributes from either trusted to untrusted or from untrusted to trusted when converting from one fabric protocol to another.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The translation must map signals in such a way that untrusted agents cannot map to trusted agents or vice-versa.
- **Implementation:** Ensure that the translation maps signals in such a way that untrusted agents cannot map to trusted agents or vice-versa.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1311 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1311.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
