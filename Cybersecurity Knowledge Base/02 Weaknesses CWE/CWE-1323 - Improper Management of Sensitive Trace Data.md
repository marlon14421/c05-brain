---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1323"
status: "Draft"
---
# CWE-1323: Improper Management of Sensitive Trace Data

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Description

Trace data collected from several sources on the System-on-Chip (SoC) is stored in unprotected locations or transported to untrusted agents.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Tag traces to indicate owner and debugging privilege level (designer, OEM, or end user) needed to access that trace.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1323 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1323.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
