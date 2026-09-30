---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-93"
status: "Draft"
---
# CWE-93: Improper Neutralization of CRLF Sequences ('CRLF Injection')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses CRLF (carriage return line feeds) as a special element, e.g. to separate lines or records, but it does not neutralize or incorrectly neutralizes CRLF sequences from inputs.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Avoid using CRLF as a special sequence.
- **Implementation:** Appropriately filter or quote CRLF sequences in user-controlled input.

## Related weaknesses

- CWE-74 (ChildOf)
- CWE-117 (CanPrecede)

## Source

- [CWE-93 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/93.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
