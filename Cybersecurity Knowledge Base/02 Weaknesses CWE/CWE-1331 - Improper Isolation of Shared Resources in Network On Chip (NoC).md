---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1331"
status: "Stable"
---
# CWE-1331: Improper Isolation of Shared Resources in Network On Chip (NoC)

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Security Hardware, Not Technology-Specific

## Description

The Network On Chip (NoC) does not isolate or incorrectly isolates its on-chip-fabric and internal resources such that they are shared between trusted and untrusted agents, creating timing channels.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Implement priority-based arbitration inside the NoC and have dedicated buffers or virtual channels for routing secret data from trusted agents.

## Related weaknesses

- CWE-653 (ChildOf)
- CWE-668 (ChildOf)
- CWE-1189 (PeerOf)

## Source

- [CWE-1331 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1331.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
