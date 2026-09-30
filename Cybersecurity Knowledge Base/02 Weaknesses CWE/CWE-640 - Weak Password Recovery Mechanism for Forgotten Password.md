---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-640"
status: "Incomplete"
---
# CWE-640: Weak Password Recovery Mechanism for Forgotten Password

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product contains a mechanism for users to recover or change their passwords without knowing the original password, but the mechanism is weak.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Make sure that all input supplied by the user to the password recovery mechanism is thoroughly filtered and validated.
- **Architecture and Design:** Do not use standard weak security questions and use several security questions.
- **Architecture and Design:** Make sure that there is throttling on the number of incorrect answers to a security question. Disable the password recovery functionality after a certain (small) number of incorrect guesses.
- **Architecture and Design:** Require that the user properly answers the security question prior to resetting their password and sending the new password to the e-mail address of record.
- **Architecture and Design:** Never allow the user to control what e-mail address the new password will be sent to in the password recovery mechanism.
- **Architecture and Design:** Assign a new temporary password rather than revealing the original password.

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-287 (ChildOf)

## Source

- [CWE-640 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/640.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
