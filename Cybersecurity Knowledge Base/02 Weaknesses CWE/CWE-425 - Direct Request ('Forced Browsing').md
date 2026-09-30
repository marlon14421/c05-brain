---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-425"
status: "Incomplete"
---
# CWE-425: Direct Request ('Forced Browsing')

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The web application does not adequately enforce appropriate authorization on all restricted URLs, scripts, or files.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Apply appropriate access control authorizations for each access to all restricted URLs, scripts or files.
- **Architecture and Design:** Consider using MVC based frameworks such as Struts.

## Related weaknesses

- CWE-862 (ChildOf)
- CWE-862 (ChildOf)
- CWE-288 (ChildOf)
- CWE-424 (ChildOf)
- CWE-471 (CanPrecede)
- CWE-98 (CanPrecede)

## Source

- [CWE-425 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/425.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
