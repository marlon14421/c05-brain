---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-593"
status: "Draft"
---
# CWE-593: Authentication Bypass: OpenSSL CTX Object Modified after SSL Objects are Created

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product modifies the SSL context after connection creation has begun.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a language or a library that provides a cryptography framework at a higher level of abstraction.
- **Implementation:** Most SSL_CTX functions have SSL counterparts that act on SSL-type objects.
- **Implementation:** Applications should set up an SSL_CTX completely, before creating SSL objects from it.

## Related weaknesses

- CWE-666 (ChildOf)
- CWE-1390 (ChildOf)

## Source

- [CWE-593 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/593.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
