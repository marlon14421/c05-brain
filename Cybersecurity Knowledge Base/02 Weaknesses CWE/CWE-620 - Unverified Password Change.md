---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-620"
status: "Draft"
---
# CWE-620: Unverified Password Change

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

When setting a new password for a user, the product does not require knowledge of the original password, or using another form of authentication.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When prompting for a password change, force the user to provide the original password in addition to the new password.
- **Architecture and Design:** Do not use "forgotten password" functionality. But if you must, ensure that you are only providing information to the actual user, e.g. by using an email address or challenge question that the legitimate user already provided in the past; do not allow the current user to change this identity information until the correct password has been provided.

## Related weaknesses

- CWE-1390 (ChildOf)

## Source

- [CWE-620 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/620.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
