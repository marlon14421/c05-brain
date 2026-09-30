---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-649"
status: "Incomplete"
---
# CWE-649: Reliance on Obfuscation or Encryption of Security-Relevant Inputs without Integrity Checking

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses obfuscation or encryption of inputs that should not be mutable by an external actor, but the product does not use integrity checks to detect if those inputs have been modified.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Protect important client controllable tokens/parameters for integrity using PKI methods (i.e. digital signatures) or other means, and checks for integrity on the server side.
- **Architecture and Design:** Repeated requests from a particular user that include invalid values of tokens/parameters (those that should not be changed manually by users) should result in the user account lockout.
- **Architecture and Design:** Client side tokens/parameters should not be such that it would be easy/predictable to guess another valid state.
- **Architecture and Design:** Obfuscation should not be relied upon. If encryption is used, it needs to be properly applied (i.e. proven algorithm and implementation, use padding, use random initialization vector, user proper encryption mode). Even with proper encryption where the ciphertext does not leak information about the plaintext or reveal its structure, compromising integrity is possible (although less likely) without the provision of the integrity service.

## Related weaknesses

- CWE-345 (ChildOf)

## Source

- [CWE-649 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/649.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
