---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-648"
status: "Incomplete"
---
# CWE-648: Incorrect Use of Privileged APIs

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product does not conform to the API requirements for a function call that requires extra privileges. This could allow attackers to gain privileges by causing the function to be called incorrectly.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Before calling privileged APIs, always ensure that the assumptions made by the privileged code hold true prior to making the call.
- **Architecture and Design:** Know architecture and implementation weaknesses of the privileged APIs and make sure to account for these weaknesses before calling the privileged APIs to ensure that they can be called safely.
- **Implementation:** If privileged APIs make certain assumptions about data, context or state validity that are passed by the caller, the calling code must ensure that these assumptions have been validated prior to making the call.
- **Implementation:** If privileged APIs do not shed their privilege prior to returning to the calling code, then calling code needs to shed these privileges immediately and safely right after the call to the privileged APIs. In particular, the calling code needs to ensure that a privileged thread of execution will never be returned to the user or made available to user-controlled processes.
- **Implementation:** Only call privileged APIs from safe, consistent and expected state.
- **Implementation:** Ensure that a failure or an error will not leave a system in a state where privileges are not properly shed and privilege escalation is possible (i.e. fail securely with regards to handling of privileges).

## Related weaknesses

- CWE-269 (ChildOf)

## Source

- [CWE-648 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/648.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
