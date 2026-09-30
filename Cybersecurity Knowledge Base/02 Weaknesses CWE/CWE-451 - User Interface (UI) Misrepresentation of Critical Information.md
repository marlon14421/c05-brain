---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-451"
status: "Draft"
---
# CWE-451: User Interface (UI) Misrepresentation of Critical Information

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Technology-Specific

## Description

The user interface (UI) does not properly represent critical information to the user, allowing the information - or its source - to be obscured or spoofed. This is often a component in phishing attacks.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Perform data validation (e.g. syntax, length, etc.) before interpreting the data.
- **Architecture and Design:** Create a strategy for presenting information, and plan for how to display unusual characters.

## Related weaknesses

- CWE-684 (ChildOf)
- CWE-221 (ChildOf)
- CWE-346 (PeerOf)

## Source

- [CWE-451 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/451.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
