---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-433"
status: "Incomplete"
---
# CWE-433: Unparsed Raw Web Content Delivery

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product stores raw content or supporting code under the web document root with an extension that is not specifically handled by the server.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Perform a type check before interpreting files.
- **Architecture and Design:** Do not store sensitive information in files which may be misinterpreted.

## Related weaknesses

- CWE-219 (ChildOf)

## Source

- [CWE-433 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/433.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
