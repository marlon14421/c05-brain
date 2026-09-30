---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-384"
status: "Incomplete"
---
# CWE-384: Session Fixation

**Abstraction:** Compound  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

Authenticating a user, or otherwise establishing a new user session, without invalidating any existing session identifier gives an attacker the opportunity to steal authenticated sessions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Invalidate any existing session identifiers prior to authorizing a new user session.
- **Architecture and Design:** For platforms such as ASP that do not generate new values for sessionid cookies, utilize a secondary cookie. In this approach, set a secondary cookie on the user's browser to a random value and set a session variable to the same value. If the session variable and the cookie value ever don't match, invalidate the session, and force the user to log on again.
- **Operation:** Use an application firewall that can detect attacks against this weakness. It can be beneficial in cases in which the code cannot be fixed (because it is controlled by a third party), as an emergency prevention measure while more comprehensive software assurance measures are applied, or to provide defense in depth [REF-1481].

## Related weaknesses

- CWE-610 (ChildOf)
- CWE-610 (ChildOf)
- CWE-346 (Requires)
- CWE-472 (Requires)
- CWE-441 (Requires)

## Source

- [CWE-384 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/384.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
