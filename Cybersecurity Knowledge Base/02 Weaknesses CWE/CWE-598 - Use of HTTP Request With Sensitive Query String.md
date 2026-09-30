---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-598"
status: "Draft"
---
# CWE-598: Use of HTTP Request With Sensitive Query String

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The web application uses an HTTP method to process a request, but the request includes sensitive information in the query string.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When sending sensitive information, only include it in the request body or request headers instead of the query string. This may require avoiding use of GET requests.

## Related weaknesses

- CWE-201 (ChildOf)

## Source

- [CWE-598 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/598.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
