---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1280"
status: "Incomplete"
---
# CWE-1280: Access Control Check Implemented After Asset is Accessed

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Verilog, VHDL, Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

A product's hardware-based access control check occurs after the asset has been accessed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Implement the access control check first. Access should only be given to asset if agent is authorized.

## Related weaknesses

- CWE-696 (ChildOf)
- CWE-284 (ChildOf)

## Source

- [CWE-1280 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1280.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
