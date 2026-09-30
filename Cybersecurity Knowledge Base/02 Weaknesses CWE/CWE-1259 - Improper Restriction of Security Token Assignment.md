---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1259"
status: "Incomplete"
---
# CWE-1259: Improper Restriction of Security Token Assignment

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Processor Hardware, System on Chip

## Description

The System-On-A-Chip (SoC) implements a Security Token mechanism to differentiate what actions are allowed or disallowed when a transaction originates from an entity. However, the Security Tokens are improperly protected.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-1294 (ChildOf)

## Source

- [CWE-1259 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1259.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
