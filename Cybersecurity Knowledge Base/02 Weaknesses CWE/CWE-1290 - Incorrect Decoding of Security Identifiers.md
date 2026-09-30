---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1290"
status: "Incomplete"
---
# CWE-1290: Incorrect Decoding of Security Identifiers

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Bus/Interface Hardware, Not Technology-Specific

## Description

The product implements a decoding mechanism to decode certain bus-transaction signals to security identifiers. If the decoding is implemented incorrectly, then untrusted agents can now gain unauthorized access to the asset.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Security identifier decoders must be reviewed for design consistency and common weaknesses.
- **Implementation:** Access and programming flows must be tested in pre-silicon and post-silicon testing in order to check for this weakness.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-1294 (ChildOf)

## Source

- [CWE-1290 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1290.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
