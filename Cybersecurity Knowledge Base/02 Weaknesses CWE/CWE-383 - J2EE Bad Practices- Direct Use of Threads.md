---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-383"
status: "Draft"
---
# CWE-383: J2EE Bad Practices: Direct Use of Threads

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java, Web Based, Web Server

## Description

Thread management in a Web application is forbidden in some circumstances and is always highly error prone.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** For EJB, use framework approaches for parallel execution, instead of using threads.

## Related weaknesses

- CWE-695 (ChildOf)

## Source

- [CWE-383 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/383.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
