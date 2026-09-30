---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-488"
status: "Draft"
---
# CWE-488: Exposure of Data Element to Wrong Session

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not sufficiently enforce boundaries between the states of different sessions, causing data to be provided to, or used by, the wrong session.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Protect the application's sessions from information leakage. Make sure that a session's data is not used or visible by other sessions.
- **Testing:** Use a static analysis tool to scan the code for information leakage vulnerabilities (e.g. Singleton Member Field).
- **Architecture and Design:** In a multithreading environment, storing user data in Servlet member fields introduces a data access race condition. Do not use member fields to store information in the Servlet.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-488 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/488.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
