---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-352"
status: "Stable"
---
# CWE-352: Cross-Site Request Forgery (CSRF)

**Abstraction:** Compound  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The web application does not, or cannot, sufficiently verify whether a request was intentionally provided by the user who sent the request, which could have originated from an unauthorized actor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that the application is free of cross-site scripting issues (CWE-79), because most CSRF defenses can be bypassed using attacker-controlled script.
- **Architecture and Design:** Generate a unique nonce for each form, place the nonce into the form, and verify the nonce upon receipt of the form. Be sure that the nonce is not predictable (CWE-330). [REF-332]
- **Architecture and Design:** Identify especially dangerous operations. When the user performs a dangerous operation, send a separate confirmation request to ensure that the user intended to perform that operation.
- **Architecture and Design:** Do not use the GET method for any request that triggers a state change.
- **Implementation:** Check the HTTP Referer header to see if the request originated from an expected page. This could break legitimate functionality, because users or proxies may have disabled sending the Referer for privacy reasons.

## Related weaknesses

- CWE-345 (ChildOf)
- CWE-345 (ChildOf)
- CWE-346 (Requires)
- CWE-441 (Requires)
- CWE-642 (Requires)
- CWE-613 (Requires)

## Source

- [CWE-352 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/352.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
