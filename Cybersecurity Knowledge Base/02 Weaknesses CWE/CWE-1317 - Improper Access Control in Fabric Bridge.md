---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1317"
status: "Draft"
---
# CWE-1317: Improper Access Control in Fabric Bridge

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Processor Hardware, Not Technology-Specific

## Description

The product uses a fabric bridge for transactions between two Intellectual Property (IP) blocks, but the bridge does not properly perform the expected privilege, identity, or other access control checks between those IP blocks.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that the design includes provisions for access-control checks in the bridge for both upstream and downstream transactions.
- **Implementation:** Implement access-control checks in the bridge for both upstream and downstream transactions.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1317 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1317.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
