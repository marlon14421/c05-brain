---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-521"
status: "Draft"
---
# CWE-521: Weak Password Requirements

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product does not require that users should have strong passwords.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Consider a second authentication factor beyond the password, which prevents the password from being a single point of failure. See CWE-308 for further information.
- **Implementation:** Consider implementing a password complexity meter to inform users when a chosen password meets the required attributes.
- **Implementation:** Previously, "password expiration" was widely advocated as a defense-in-depth approach to minimize the risk of weak passwords, and it has become a common practice. Password expiration requires a password to be changed within a fixed time window (such as every 90 days). However, this approach has significant limitations in the current threat landscape, and its utility has been reduced in light of the adoption of related protection mechanisms (such as password complexity and computational effort), along with the recognition that regular password changes often caused users to generate more predictable passwords. As a result, this is now a Discouraged Common Practice [REF-1488] [REF-1489], especially as the sole factor in protecting passwords. It is still strongly encouraged to force password changes in case of evidence of compromise, but this is not the same as a forced "expiration" on an arbitrary time frame.

## Related weaknesses

- CWE-1391 (ChildOf)
- CWE-287 (ChildOf)

## Source

- [CWE-521 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/521.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
