---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-444"
status: "Incomplete"
---
# CWE-444: Inconsistent Interpretation of HTTP Requests ('HTTP Request/Response Smuggling')

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product acts as an intermediary HTTP agent (such as a proxy or firewall) in the data flow between two entities such as a client and server, but it does not interpret malformed HTTP requests or responses in ways that are consistent with how the messages will be processed by those entities that are at the ultimate destination.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use a web server that employs a strict HTTP parsing procedure, such as Apache [REF-433].
- **Implementation:** Use only SSL communication.
- **Implementation:** Terminate the client session after each request.
- **System Configuration:** Turn all pages to non-cacheable.

## Related weaknesses

- CWE-436 (ChildOf)
- CWE-436 (ChildOf)

## Source

- [CWE-444 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/444.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
