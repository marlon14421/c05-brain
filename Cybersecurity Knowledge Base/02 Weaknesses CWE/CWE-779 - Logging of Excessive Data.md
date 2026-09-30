---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-779"
status: "Draft"
---
# CWE-779: Logging of Excessive Data

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product logs too much information, making log files hard to process and possibly hindering recovery efforts or forensic analysis after an attack.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Suppress large numbers of duplicate log messages and replace them with periodic summaries. For example, syslog may include an entry that states "last message repeated X times" when recording repeated events.
- **Architecture and Design:** Support a maximum size for the log file that can be controlled by the administrator. If the maximum size is reached, the admin should be notified. Also, consider reducing functionality of the product. This may result in a denial-of-service to legitimate product users, but it will prevent the product from adversely impacting the entire system.
- **Implementation:** Adjust configurations appropriately when the product is transitioned from a debug state to production.

## Related weaknesses

- CWE-400 (ChildOf)

## Source

- [CWE-779 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/779.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
