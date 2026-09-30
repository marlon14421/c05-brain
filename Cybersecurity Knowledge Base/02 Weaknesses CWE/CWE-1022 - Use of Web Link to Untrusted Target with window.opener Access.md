---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1022"
status: "Incomplete"
---
# CWE-1022: Use of Web Link to Untrusted Target with window.opener Access

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, JavaScript, Web Based, Web Server

## Description

The web application produces links to untrusted external sites outside of its sphere of control, but it does not properly prevent the external site from modifying security-critical properties of the window.opener object, such as the location property.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Specify in the design that any linked external document must not be granted access to the location object of the calling page.

## Related weaknesses

- CWE-266 (ChildOf)

## Source

- [CWE-1022 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1022.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
