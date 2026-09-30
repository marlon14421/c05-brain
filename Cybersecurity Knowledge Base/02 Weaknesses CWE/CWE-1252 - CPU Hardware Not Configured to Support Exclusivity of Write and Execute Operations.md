---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1252"
status: "Incomplete"
---
# CWE-1252: CPU Hardware Not Configured to Support Exclusivity of Write and Execute Operations

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Microcontroller Hardware, Processor Hardware

## Description

The CPU is not configured to provide hardware support for exclusivity of write and execute operations on memory. This allows an attacker to execute data from all of memory.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1252 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1252.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
