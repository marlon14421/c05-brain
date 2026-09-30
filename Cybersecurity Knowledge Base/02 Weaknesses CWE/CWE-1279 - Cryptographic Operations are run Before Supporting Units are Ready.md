---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1279"
status: "Incomplete"
---
# CWE-1279: Cryptographic Operations are run Before Supporting Units are Ready

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Verilog, VHDL, Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Processor Hardware, Not Technology-Specific

## Description

Performing cryptographic operations without ensuring that the supporting inputs are ready to supply valid data may compromise the cryptographic result.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Best practices should be used to design cryptographic systems.
- **Implementation:** Continuously ensuring that cryptographic inputs are supplying valid information is necessary to ensure that the encrypted output is secure.

## Related weaknesses

- CWE-696 (ChildOf)
- CWE-665 (ChildOf)

## Source

- [CWE-1279 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1279.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
