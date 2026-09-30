---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-551"
status: "Incomplete"
---
# CWE-551: Incorrect Behavior Order: Authorization Before Parsing and Canonicalization

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based, Web Server

## Description

If a web server does not fully parse requested URLs before it examines them for authorization, it may be possible for an attacker to bypass authorization protection.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** URL Inputs should be decoded and canonicalized to the application's current internal representation before being validated and processed for authorization. Make sure that your application does not decode the same input twice. Such errors could be used to bypass allowlist schemes by introducing dangerous inputs after they have been checked.

## Related weaknesses

- CWE-863 (ChildOf)
- CWE-696 (ChildOf)
- CWE-41 (PeerOf)

## Source

- [CWE-551 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/551.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
