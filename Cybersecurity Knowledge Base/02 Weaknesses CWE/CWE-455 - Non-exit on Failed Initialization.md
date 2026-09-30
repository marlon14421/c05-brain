---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-455"
status: "Draft"
---
# CWE-455: Non-exit on Failed Initialization

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not exit or otherwise modify its operation when security-relevant errors occur during initialization, such as when a configuration file has a format error or a hardware security module (HSM) cannot be activated, which can cause the product to execute in a less secure fashion than intended by the administrator.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Follow the principle of failing securely when an error occurs. The system should enter a state where it is not vulnerable and will not display sensitive error messages to a potential attacker.

## Related weaknesses

- CWE-665 (ChildOf)
- CWE-705 (ChildOf)
- CWE-636 (ChildOf)

## Source

- [CWE-455 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/455.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
