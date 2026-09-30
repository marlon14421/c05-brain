---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1294"
status: "Incomplete"
---
# CWE-1294: Insecure Security Identifier Mechanism

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Bus/Interface Hardware, Not Technology-Specific

## Description

The System-on-Chip (SoC) implements a Security Identifier mechanism to differentiate what actions are allowed or disallowed when a transaction originates from an entity. However, the Security Identifiers are not correctly implemented.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Security Identifier Decoders must be reviewed for design inconsistency and common weaknesses.
- **Implementation:** Access and programming flows must be tested in pre-silicon and post-silicon testing.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1294 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1294.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
