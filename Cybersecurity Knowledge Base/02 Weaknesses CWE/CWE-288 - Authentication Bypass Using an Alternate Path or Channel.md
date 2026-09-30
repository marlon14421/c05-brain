---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-288"
status: "Incomplete"
---
# CWE-288: Authentication Bypass Using an Alternate Path or Channel

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

The product requires authentication, but the product has an alternate path or channel that does not require authentication.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Funnel all access through a single choke point to simplify how users can access a resource. For every access, perform a check to determine if the user has permissions to access the resource.

## Related weaknesses

- CWE-306 (ChildOf)
- CWE-284 (ChildOf)
- CWE-420 (PeerOf)

## Source

- [CWE-288 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/288.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
