---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-553"
status: "Incomplete"
---
# CWE-553: Command Shell in Externally Accessible Directory

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based, Web Server

## Description

A possible shell file exists in /cgi-bin/ or other accessible directories. This is extremely dangerous and can be used by an attacker to execute commands on the web server.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Installation:** Remove any Shells accessible under the web root folder and children directories.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-553 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/553.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
