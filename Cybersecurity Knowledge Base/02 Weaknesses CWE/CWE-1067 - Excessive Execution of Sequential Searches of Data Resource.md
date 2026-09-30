---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1067"
status: "Incomplete"
---
# CWE-1067: Excessive Execution of Sequential Searches of Data Resource

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product contains a data query against an SQL table or view that is configured in a way that does not utilize an index and may cause sequential searches to be performed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-1176 (ChildOf)

## Source

- [CWE-1067 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1067.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
