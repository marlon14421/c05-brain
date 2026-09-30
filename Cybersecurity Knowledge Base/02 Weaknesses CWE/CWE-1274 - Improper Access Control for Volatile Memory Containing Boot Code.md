---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1274"
status: "Stable"
---
# CWE-1274: Improper Access Control for Volatile Memory Containing Boot Code

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product conducts a secure-boot process that transfers bootloader code from Non-Volatile Memory (NVM) into Volatile Memory (VM), but it does not have sufficient access control or other protections for the Volatile Memory.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that the design of volatile-memory protections is enough to prevent modification from an adversary or untrusted code.
- **Testing:** Test the volatile-memory protections to ensure they are safe from modification or untrusted code.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1274 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1274.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
