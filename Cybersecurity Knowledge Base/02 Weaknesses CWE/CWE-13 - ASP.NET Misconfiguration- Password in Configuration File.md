---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-13"
status: "Draft"
---
# CWE-13: ASP.NET Misconfiguration: Password in Configuration File

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** ASP.NET

## Description

Storing a plaintext password in a configuration file allows anyone who can read the file access to the password-protected resource making them an easy target for attackers.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Credentials stored in configuration files should be encrypted, Use standard APIs and industry accepted algorithms to encrypt the credentials stored in configuration files.

## Related weaknesses

- CWE-260 (ChildOf)

## Source

- [CWE-13 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/13.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
