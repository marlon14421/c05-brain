---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-263"
status: "Draft"
---
# CWE-263: Password Aging with Long Expiration

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product supports password aging, but the expiration period is too long.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Previously, "password expiration" was widely advocated as a defense-in-depth approach to minimize the risk of weak passwords, and it has become a common practice. Password expiration requires a password to be changed within a fixed time window (such as every 90 days). However, this approach has significant limitations in the current threat landscape, and its utility has been reduced in light of the adoption of related protection mechanisms (such as password complexity and computational effort), along with the recognition that regular password changes often caused users to generate more predictable passwords. As a result, this is now a Discouraged Common Practice [REF-1488] [REF-1489], especially as the sole factor in protecting passwords. It is still strongly encouraged to force password changes in case of evidence of compromise, but this is not the same as a forced "expiration" on an arbitrary time frame.
- **Architecture and Design:** Ensure that password aging is limited so that there is a defined maximum age for passwords. Note that if the expiration window is too short, it can cause users to generate poor or predictable passwords.
- **Architecture and Design:** Ensure that the user is notified several times leading up to the password expiration.
- **Architecture and Design:** Create mechanisms to prevent users from reusing passwords or creating similar passwords.
- **Implementation:** Developers might disable clipboard paste operations into password fields as a way to discourage users from pasting a password into a clipboard. However, this might encourage users to choose less-secure passwords that are easier to type, and it can reduce the usability of password managers [REF-1294].

## Related weaknesses

- CWE-1390 (ChildOf)

## Source

- [CWE-263 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/263.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
