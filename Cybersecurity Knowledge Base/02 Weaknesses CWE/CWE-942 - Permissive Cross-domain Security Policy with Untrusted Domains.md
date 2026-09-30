---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-942"
status: "Incomplete"
---
# CWE-942: Permissive Cross-domain Security Policy with Untrusted Domains

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product uses a web-client protection mechanism such as a Content Security Policy (CSP) or cross-domain policy file, but the policy includes untrusted domains with which the web client is allowed to communicate.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Define a restrictive Content Security Policy [REF-1486] or cross-domain policy file.
- **Architecture and Design:** Avoid using wildcards in the CSP / cross-domain policy file. Any domain matching the wildcard expression will be implicitly trusted, and can perform two-way interaction with the target server.
- **Architecture and Design:** For Flash, modify crossdomain.xml to use meta-policy options such as 'master-only' or 'none' to reduce the possibility of an attacker planting extraneous cross-domain policy files on a server.

## Related weaknesses

- CWE-863 (ChildOf)
- CWE-923 (ChildOf)
- CWE-183 (ChildOf)
- CWE-668 (CanPrecede)

## Source

- [CWE-942 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/942.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
