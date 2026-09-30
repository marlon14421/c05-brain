---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-539"
status: "Incomplete"
---
# CWE-539: Use of Persistent Cookies Containing Sensitive Information

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The web application uses persistent cookies, but the cookies contain sensitive information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not store sensitive information in persistent cookies.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-539 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/539.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
