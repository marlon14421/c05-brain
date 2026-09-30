---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1389"
status: "Incomplete"
---
# CWE-1389: Incorrect Parsing of Numbers with Different Radices

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product parses numeric input assuming base 10 (decimal) values, but it does not account for inputs that use a different base number (radix).

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If only decimal-based values are expected in the application, conditional checks should be created in a way that prevent octal or hexadecimal strings from being checked. This can be achieved by converting any numerical string to an explicit base-10 integer prior to the conditional check, to prevent octal or hex values from ever being checked against the condition.
- **Implementation:** If various numerical bases do need to be supported, check for leading values indicating the non-decimal base you wish to support (such as 0x for hex) and convert the numeric strings to integers of the respective base. Reject any other alternative-base string that is not intentionally supported by the application.
- **Implementation:** If regular expressions are used to validate IP addresses, ensure that they are bounded using ^ and $ to prevent base-prepended IP addresses from being matched.

## Related weaknesses

- CWE-704 (ChildOf)

## Source

- [CWE-1389 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1389.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
