---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-319"
status: "Draft"
---
# CWE-319: Cleartext Transmission of Sensitive Information

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Cloud Computing, Mobile, ICS/OT, System on Chip, Test/Debug Hardware

## Description

The product transmits sensitive or security-critical data in cleartext in a communication channel that can be sniffed by unauthorized actors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Before transmitting, encrypt the data using reliable, confidentiality-protecting cryptographic protocols.
- **Implementation:** When using web applications with SSL, use SSL for the entire session from login to logout, not just for the initial login page.
- **Implementation:** When designing hardware platforms, ensure that approved encryption algorithms (such as those recommended by NIST) protect paths from security critical data to trusted user applications.
- **Testing:** Use tools and techniques that require manual (human) analysis, such as penetration testing, threat modeling, and interactive tools that allow the tester to record and modify an active session. These may be more effective than strictly automated techniques. This is especially the case with weaknesses that are related to design and business rules.
- **Operation:** Configure servers to use encrypted channels for communication, which may include SSL or other secure protocols.

## Related weaknesses

- CWE-311 (ChildOf)
- CWE-311 (ChildOf)

## Source

- [CWE-319 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/319.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
