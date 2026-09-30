---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-619"
status: "Incomplete"
---
# CWE-619: Dangling Database Cursor ('Cursor Injection')

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** SQL, Database Server

## Description

If a database cursor is not closed properly, then it could become accessible to other users while retaining the same privileges that were originally assigned, leaving the cursor "dangling."

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Close cursors immediately after access to them is complete. Ensure that you close cursors if exceptions occur.

## Related weaknesses

- CWE-402 (ChildOf)

## Source

- [CWE-619 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/619.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
