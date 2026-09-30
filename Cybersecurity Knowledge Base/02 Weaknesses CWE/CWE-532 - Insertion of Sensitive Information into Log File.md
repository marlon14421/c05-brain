---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-532"
status: "Incomplete"
---
# CWE-532: Insertion of Sensitive Information into Log File

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product writes sensitive information to a log file.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Consider seriously the sensitivity of the information written into log files. Do not write secrets into the log files.
- **Distribution:** Remove debug log files before deploying the application into production.
- **Operation:** Protect log files against unauthorized read/write.
- **Implementation:** Adjust configurations appropriately when software is transitioned from a debug state to production.

## Related weaknesses

- CWE-538 (ChildOf)
- CWE-200 (ChildOf)

## Source

- [CWE-532 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/532.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
