---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1253"
status: "Draft"
---
# CWE-1253: Incorrect Selection of Fuse Values

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The logic level used to set a system to a secure state relies on a fuse being unblown.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Logic should be designed in a way that blown fuses do not put the product into an insecure state that can be leveraged by an attacker.

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-1253 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1253.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
