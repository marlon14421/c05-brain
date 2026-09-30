---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1271"
status: "Incomplete"
---
# CWE-1271: Uninitialized Value on Reset for Registers Holding Security Settings

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

Security-critical logic is not set to a known value on reset.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Design checks should be performed to identify any uninitialized flip-flops used for security-critical functions.
- **Architecture and Design:** All registers holding security-critical information should be set to a specific value on reset.

## Related weaknesses

- CWE-909 (ChildOf)

## Source

- [CWE-1271 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1271.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
