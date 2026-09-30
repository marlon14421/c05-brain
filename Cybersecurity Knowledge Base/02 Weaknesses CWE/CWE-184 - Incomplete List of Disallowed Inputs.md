---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-184"
status: "Draft"
---
# CWE-184: Incomplete List of Disallowed Inputs

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product implements a protection mechanism that relies on a list of inputs (or properties of inputs) that are not allowed by policy or otherwise require other action to neutralize before additional processing takes place, but the list is incomplete.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not rely exclusively on detecting disallowed inputs. There are too many variants to encode a character, especially when different environments are used, so there is a high likelihood of missing some variants. Only use detection of disallowed inputs as a mechanism for detecting suspicious activity. Ensure that you are using other protection mechanisms that only identify "good" input - such as lists of allowed inputs - and ensure that you are properly encoding your outputs.

## Related weaknesses

- CWE-693 (ChildOf)
- CWE-1023 (ChildOf)
- CWE-79 (CanPrecede)
- CWE-78 (CanPrecede)
- CWE-434 (CanPrecede)
- CWE-98 (CanPrecede)

## Source

- [CWE-184 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/184.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
