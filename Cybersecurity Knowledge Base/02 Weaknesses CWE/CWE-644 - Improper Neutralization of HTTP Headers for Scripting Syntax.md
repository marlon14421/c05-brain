---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-644"
status: "Incomplete"
---
# CWE-644: Improper Neutralization of HTTP Headers for Scripting Syntax

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

The product does not neutralize or incorrectly neutralizes web scripting syntax in HTTP headers that can be used by web browser components that can process raw headers, such as Flash.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Perform output validation in order to filter/escape/encode unsafe data that is being passed from the server in an HTTP response header.
- **Architecture and Design:** Disable script execution functionality in the clients' browser.

## Related weaknesses

- CWE-116 (ChildOf)

## Source

- [CWE-644 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/644.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
