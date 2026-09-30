---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1021"
status: "Incomplete"
---
# CWE-1021: Improper Restriction of Rendered UI Layers or Frames

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

The web application does not restrict or incorrectly restricts frame objects or UI layers that belong to another application or domain.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** This defense-in-depth technique can be used to prevent the improper usage of frames in web applications. It prioritizes the valid sources of data to be loaded into the application through the usage of declarative policies. Based on which implementation of Content Security Policy is in use, the developer should use the "frame-ancestors" directive or the "frame-src" directive to mitigate this weakness. Both directives allow for the placement of restrictions when it comes to allowing embedded content.
- **Implementation:** In addition to frames or iframes as previously mentioned, the web application is expected to place restrictions on whether it is allowed to be rendered within objects, embed, or applet elements.

## Related weaknesses

- CWE-441 (ChildOf)
- CWE-610 (ChildOf)
- CWE-451 (ChildOf)

## Source

- [CWE-1021 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1021.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
