---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1275"
status: "Incomplete"
---
# CWE-1275: Sensitive Cookie with Improper SameSite Attribute

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Web Based, Web Server

## Description

The SameSite attribute for sensitive cookies is not set, or an insecure value is used.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Set the SameSite attribute of a sensitive cookie to 'Lax' or 'Strict'. This instructs the browser to apply this cookie only to same-domain requests, which provides a good Defense in Depth against CSRF attacks. When the 'Lax' value is in use, cookies are also sent for top-level cross-domain navigation via HTTP GET, HEAD, OPTIONS, and TRACE methods, but not for other HTTP methods that are more like to cause side-effects of state mutation.

## Related weaknesses

- CWE-923 (ChildOf)
- CWE-352 (CanPrecede)

## Source

- [CWE-1275 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1275.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
