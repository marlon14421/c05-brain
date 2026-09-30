---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-419"
status: "Draft"
---
# CWE-419: Unprotected Primary Channel

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses a primary channel for administration or restricted functionality, but it does not properly protect the channel.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not expose administrative functionnality on the user UI.
- **Architecture and Design:** Protect the administrative/restricted functionality with a strong authentication mechanism.

## Related weaknesses

- CWE-923 (ChildOf)

## Source

- [CWE-419 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/419.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
