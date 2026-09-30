---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1295"
status: "Incomplete"
---
# CWE-1295: Debug Messages Revealing Unnecessary Information

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product fails to adequately prevent the revealing of unnecessary and potentially sensitive system information within debugging messages.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that a debug message does not reveal any unnecessary information during the debug process for the intended response.

## Related weaknesses

- CWE-200 (ChildOf)
- CWE-209 (PeerOf)

## Source

- [CWE-1295 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1295.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
