---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-572"
status: "Draft"
---
# CWE-572: Call to Thread run() instead of start()

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product calls a thread's run() method instead of calling start(), which causes the code to run in the thread of the caller instead of the callee.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use the start() method instead of the run() method.

## Related weaknesses

- CWE-821 (ChildOf)

## Source

- [CWE-572 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/572.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
