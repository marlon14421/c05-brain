---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-645"
status: "Incomplete"
---
# CWE-645: Overly Restrictive Account Lockout Mechanism

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product contains an account lockout protection mechanism, but the mechanism is too restrictive and can be triggered too easily, which allows attackers to deny service to legitimate users by causing their accounts to be locked out.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Implement more intelligent password throttling mechanisms such as those which take IP address into account, in addition to the login name.
- **Architecture and Design:** Implement a lockout timeout that grows as the number of incorrect login attempts goes up, eventually resulting in a complete lockout.
- **Architecture and Design:** Consider alternatives to account lockout that would still be effective against password brute force attacks, such as presenting the user machine with a puzzle to solve (makes it do some computation).

## Related weaknesses

- CWE-287 (ChildOf)

## Source

- [CWE-645 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/645.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
