---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1428"
status: "Incomplete"
---
# CWE-1428: Reliance on HTTP instead of HTTPS

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The product provides or relies on use of HTTP communications when HTTPS is available.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Explicitly require HTTPS or another mechanism that ensures that communication is encrypted [REF-1464].
- **Implementation:** Avoid using "mixed content," i.e., serving a web page over HTTPS in which the page includes elements that use "http:" URLs [REF-1466] [REF-1467]. This is often done for images or other resources that do not seem to have privacy or security implications.
- **Implementation:** Perform "HTTPS forcing," that is, redirecting HTTP requests to HTTPS.
- **Operation:** If the product supports multiple protocols, ensure that encrypted protocols (such as HTTPS) are required, and remove any unencrypted protocols (such as HTTP).

## Related weaknesses

- CWE-319 (ChildOf)

## Source

- [CWE-1428 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1428.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
