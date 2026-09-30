---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1246"
status: "Incomplete"
---
# CWE-1246: Improper Write Handling in Limited-write Non-Volatile Memories

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip, Memory Hardware, Storage Hardware

## Description

The product does not implement or incorrectly implements wear leveling operations in limited-write non-volatile memories.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Include secure wear leveling algorithms and ensure they may not be bypassed.

## Related weaknesses

- CWE-400 (ChildOf)

## Source

- [CWE-1246 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1246.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
