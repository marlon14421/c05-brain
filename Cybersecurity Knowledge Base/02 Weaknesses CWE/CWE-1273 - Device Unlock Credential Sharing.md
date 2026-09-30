---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1273"
status: "Incomplete"
---
# CWE-1273: Device Unlock Credential Sharing

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** VHDL, Verilog, Compiled, Not OS-Specific, Not Architecture-Specific, Other, Not Technology-Specific

## Description

The credentials necessary for unlocking a device are shared across multiple parties and may expose sensitive information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Integration:** Ensure the unlock credentials are shared with the minimum number of parties and with utmost secrecy. To limit the risk associated with compromised credentials, where possible, the credentials should be part-specific.
- **Manufacturing:** Ensure the unlock credentials are shared with the minimum number of parties and with utmost secrecy. To limit the risk associated with compromised credentials, where possible, the credentials should be part-specific.

## Related weaknesses

- CWE-200 (ChildOf)

## Source

- [CWE-1273 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1273.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
