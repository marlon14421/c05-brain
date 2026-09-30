---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-138"
status: "Draft"
---
# CWE-138: Improper Neutralization of Special Elements

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product receives input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could be interpreted as control elements or syntactic markers when they are sent to a downstream component.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Developers should anticipate that special elements (e.g. delimiters, symbols) will be injected into input vectors of their product. One defense is to create an allowlist (e.g. a regular expression) that defines valid input according to the requirements specifications. Strictly filter any input that does not match against the allowlist. Properly encode your output, and quote any elements that have special meaning to the component with which you are communicating.
- **Implementation:** Use and specify an appropriate output encoding to ensure that the special elements are well-defined. A normal byte sequence in one encoding could be a special element in another.
- **Implementation:** Inputs should be decoded and canonicalized to the application's current internal representation before being validated (CWE-180). Make sure that the application does not decode the same input twice (CWE-174). Such errors could be used to bypass allowlist validation schemes by introducing dangerous inputs after they have been checked.
- **Implementation:** While it is risky to use dynamically-generated query strings, code, or commands that mix control and data together, sometimes it may be unavoidable. Properly quote arguments and escape any special characters within those arguments. The most conservative approach is to escape or filter all characters that do not pass an extremely strict allowlist (such as everything that is not alphanumeric or white space). If some special characters are still needed, such as white space, wrap each argument in quotes after the escaping/filtering step. Be careful of argument injection (CWE-88).

## Related weaknesses

- CWE-707 (ChildOf)

## Source

- [CWE-138 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/138.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
