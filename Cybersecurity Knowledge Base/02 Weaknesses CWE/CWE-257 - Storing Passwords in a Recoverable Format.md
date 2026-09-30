---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-257"
status: "Incomplete"
---
# CWE-257: Storing Passwords in a Recoverable Format

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The storage of passwords in a recoverable format makes them subject to password reuse attacks by malicious users. In fact, it should be noted that recoverable encrypted passwords provide no significant benefit over plaintext passwords since they are subject not only to reuse by malicious attackers but also by malicious insiders. If a system administrator can recover a password directly, or use a brute force search on the available information, the administrator can use the password on other accounts.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use strong, non-reversible encryption to protect stored passwords.

## Related weaknesses

- CWE-522 (ChildOf)
- CWE-259 (PeerOf)

## Source

- [CWE-257 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/257.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
