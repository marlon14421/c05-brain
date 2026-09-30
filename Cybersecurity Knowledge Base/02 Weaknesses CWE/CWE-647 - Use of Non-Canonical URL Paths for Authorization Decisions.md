---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-647"
status: "Incomplete"
---
# CWE-647: Use of Non-Canonical URL Paths for Authorization Decisions

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Server

## Description

The product defines policy namespaces and makes authorization decisions based on the assumption that a URL is canonical. This can allow a non-canonical URL to bypass the authorization.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Make access control policy based on path information in canonical form. Use very restrictive regular expressions to validate that the path is in the expected form.
- **Architecture and Design:** Reject all alternate path encodings that are not in the expected canonical form.

## Related weaknesses

- CWE-863 (ChildOf)
- CWE-180 (ChildOf)

## Source

- [CWE-647 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/647.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
