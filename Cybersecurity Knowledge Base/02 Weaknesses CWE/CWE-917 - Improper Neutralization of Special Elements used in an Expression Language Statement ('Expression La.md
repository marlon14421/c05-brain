---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-917"
status: "Incomplete"
---
# CWE-917: Improper Neutralization of Special Elements used in an Expression Language Statement ('Expression Language Injection')

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java

## Description

The product constructs all or part of an expression language (EL) statement in a framework such as a Java Server Page (JSP) using externally-influenced input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could modify the intended EL statement before it is executed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Avoid adding user-controlled data into an expression interpreter when possible.
- **System Configuration:** The framework or tooling might allow the developer to disable or deactivate the processing of EL expressions, such as setting the isELIgnored attribute for a JSP page to "true".

## Related weaknesses

- CWE-77 (ChildOf)
- CWE-1336 (PeerOf)
- CWE-74 (ChildOf)
- CWE-77 (ChildOf)
- CWE-77 (ChildOf)

## Source

- [CWE-917 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/917.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
