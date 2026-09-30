---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1073"
status: "Incomplete"
---
# CWE-1073: Non-SQL Invokable Control Element with Excessive Number of Data Resource Accesses

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** SQL, Database Server

## Description

The product contains a client with a function or method that contains a large number of data accesses/queries that are sent through a data manager, i.e., does not use efficient database capabilities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-405 (ChildOf)

## Source

- [CWE-1073 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1073.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
