---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-327"
status: "Draft"
---
# CWE-327: Use of a Broken or Risky Cryptographic Algorithm

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Verilog, VHDL, Not Technology-Specific, ICS/OT

## Description

The product uses a broken or risky cryptographic algorithm or protocol.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that the design allows one cryptographic algorithm to be replaced with another in the next generation or version. Where possible, use wrappers to make the interfaces uniform. This will make it easier to upgrade to stronger algorithms. With hardware, design the product at the Intellectual Property (IP) level so that one cryptographic algorithm can be replaced with another in the next generation of the hardware product.
- **Architecture and Design:** Carefully manage and protect cryptographic keys (see CWE-320). If the keys can be guessed or stolen, then the strength of the cryptography itself is irrelevant.
- **Implementation:** When using industry-approved techniques, use them correctly. Don't cut corners by skipping resource-intensive steps (CWE-325). These steps are often essential for preventing common attacks.

## Related weaknesses

- CWE-693 (ChildOf)
- CWE-311 (PeerOf)

## Source

- [CWE-327 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/327.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
