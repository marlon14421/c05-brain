---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-618"
status: "Incomplete"
---
# CWE-618: Exposed Unsafe ActiveX Method

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Web Based

## Description

An ActiveX control is intended for use in a web browser, but it exposes dangerous methods that perform actions that are outside of the browser's security model (e.g. the zone or domain).

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If you must expose a method, make sure to perform input validation on all arguments, and protect against all possible vulnerabilities.
- **Architecture and Design:** Use code signing, although this does not protect against any weaknesses that are already in the control.
- **Architecture and Design:** Where possible, avoid marking the control as safe for scripting.

## Related weaknesses

- CWE-749 (ChildOf)

## Source

- [CWE-618 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/618.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
