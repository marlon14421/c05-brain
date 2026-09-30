---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-293"
status: "Draft"
---
# CWE-293: Using Referer Field for Authentication

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The referer field in HTTP requests can be easily modified and, as such, is not a valid means of message integrity checking.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** In order to usefully check if a given action is authorized, some means of strong authentication and method protection must be used. Use other means of authorization that cannot be simply spoofed. Possibilities include a username/password or certificate.

## Related weaknesses

- CWE-290 (ChildOf)

## Source

- [CWE-293 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/293.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
