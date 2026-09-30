---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1236"
status: "Incomplete"
---
# CWE-1236: Improper Neutralization of Formula Elements in a CSV File

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Other

## Description

The product saves user-provided information into a Comma-Separated Value (CSV) file, but it does not neutralize or incorrectly neutralizes special elements that could be interpreted as a command when the file is opened by a spreadsheet product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When generating CSV output, ensure that formula-sensitive metacharacters are effectively escaped or removed from all data before storage in the resultant CSV. Risky characters include '=' (equal), '+' (plus), '-' (minus), and '@' (at).
- **Implementation:** If a field starts with a formula character, prepend it with a ' (single apostrophe), which prevents Excel from executing the formula.
- **Architecture and Design:** Certain implementations of spreadsheet software might disallow formulas from executing if the file is untrusted, or if the file is not authored by the current user.

## Related weaknesses

- CWE-74 (ChildOf)
- CWE-74 (ChildOf)

## Source

- [CWE-1236 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1236.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
