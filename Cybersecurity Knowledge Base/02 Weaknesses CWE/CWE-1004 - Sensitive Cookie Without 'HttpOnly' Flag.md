---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1004"
status: "Incomplete"
---
# CWE-1004: Sensitive Cookie Without 'HttpOnly' Flag

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product uses a cookie to store sensitive information, but the cookie is not marked with the HttpOnly flag.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Leverage the HttpOnly flag when setting a sensitive cookie in a response.

## Related weaknesses

- CWE-732 (ChildOf)

## Source

- [CWE-1004 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1004.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
