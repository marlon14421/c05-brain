---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-565"
status: "Incomplete"
---
# CWE-565: Reliance on Cookies without Validation and Integrity Checking

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product relies on the existence or values of cookies when performing security-critical operations, but it does not properly ensure that the setting is valid for the associated user.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Avoid using cookie data for a security-related decision.
- **Implementation:** Perform thorough input validation (i.e.: server side validation) on the cookie data if you're going to use it for a security related decision.
- **Architecture and Design:** Add integrity checks to detect tampering.
- **Architecture and Design:** Protect critical cookies from replay attacks, since cross-site scripting or other attacks may allow attackers to steal a strongly-encrypted cookie that also passes integrity checks. This mitigation applies to cookies that should only be valid during a single transaction or session. By enforcing timeouts, you may limit the scope of an attack. As part of your integrity check, use an unpredictable, server-side value that is not exposed to the client.

## Related weaknesses

- CWE-642 (ChildOf)
- CWE-669 (ChildOf)
- CWE-602 (ChildOf)

## Source

- [CWE-565 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/565.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
