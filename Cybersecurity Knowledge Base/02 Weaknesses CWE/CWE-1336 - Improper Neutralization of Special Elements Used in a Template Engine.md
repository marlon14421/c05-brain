---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1336"
status: "Incomplete"
---
# CWE-1336: Improper Neutralization of Special Elements Used in a Template Engine

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, PHP, Python, JavaScript, Interpreted, Not OS-Specific, Not Technology-Specific, AI/ML, Client Server

## Description

The product uses a template engine to insert or process externally-influenced input, but it does not neutralize or incorrectly neutralizes special elements or syntax that can be interpreted as template expressions or other code directives when processed by the engine.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Choose a template engine that offers a sandbox or restricted mode, or at least limits the power of any available expressions, function calls, or commands.
- **Implementation:** Use the template engine's sandbox or restricted mode, if available.

## Related weaknesses

- CWE-94 (ChildOf)

## Source

- [CWE-1336 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1336.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
