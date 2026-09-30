---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-309"
status: "Draft"
---
# CWE-309: Use of Password System for Primary Authentication

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The use of password systems as the primary means of authentication may be subject to several flaws or shortcomings, each reducing the effectiveness of the mechanism.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a zero-knowledge password protocol, such as SRP.
- **Architecture and Design:** Ensure that passwords are stored safely and are not reversible.
- **Architecture and Design:** Implement password aging functionality that requires passwords be changed after a certain point.
- **Architecture and Design:** Use a mechanism for determining the strength of a password and notify the user of weak password use.
- **Architecture and Design:** Inform the user of why password protections are in place, how they work to protect data integrity, and why it is important to heed their warnings.

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-654 (ChildOf)
- CWE-308 (PeerOf)

## Source

- [CWE-309 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/309.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
