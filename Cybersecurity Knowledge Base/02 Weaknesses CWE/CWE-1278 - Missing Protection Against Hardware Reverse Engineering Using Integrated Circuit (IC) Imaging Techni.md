---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1278"
status: "Incomplete"
---
# CWE-1278: Missing Protection Against Hardware Reverse Engineering Using Integrated Circuit (IC) Imaging Techniques

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

Information stored in hardware may be recovered by an attacker with the capability to capture and analyze images of the integrated circuit using techniques such as scanning electron microscopy.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The cost of secret extraction via IC reverse engineering should outweigh the potential value of the secrets being extracted. Threat model and value of secrets should be used to choose the technology used to safeguard those secrets. Examples include IC camouflaging and obfuscation, tamper-proof packaging, active shielding, and physical tampering detection information erasure.

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-1278 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1278.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
