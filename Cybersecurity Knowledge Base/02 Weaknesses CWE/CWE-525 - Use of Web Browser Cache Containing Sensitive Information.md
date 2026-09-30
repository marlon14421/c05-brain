---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-525"
status: "Incomplete"
---
# CWE-525: Use of Web Browser Cache Containing Sensitive Information

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The web application does not use an appropriate caching policy that specifies the extent to which each web page and associated form fields should be cached.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Protect information stored in cache.
- **Implementation:** Use a restrictive caching policy for forms and web pages that potentially contain sensitive information, such as "no-cache" in the Cache-Control header.
- **Architecture and Design:** Do not store unnecessarily sensitive information in the cache.
- **Architecture and Design:** Consider using encryption in the cache.

## Related weaknesses

- CWE-524 (ChildOf)

## Source

- [CWE-525 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/525.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
