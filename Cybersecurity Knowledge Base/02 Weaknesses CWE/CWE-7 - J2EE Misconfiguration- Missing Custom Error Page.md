---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-7"
status: "Incomplete"
---
# CWE-7: J2EE Misconfiguration: Missing Custom Error Page

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, Web Based, Web Server

## Description

The default error page of a web application should not display sensitive information about the product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Handle exceptions appropriately in source code.
- **Implementation:** Always define appropriate error pages. The application configuration should specify a default error page in order to guarantee that the application will never leak error messages to an attacker. Handling standard HTTP error codes is useful and user-friendly in addition to being a good security practice, and a good configuration will also define a last-chance error handler that catches any exception that could possibly be thrown by the application.
- **Implementation:** Do not attempt to process an error or attempt to mask it.
- **Implementation:** Verify return values are correct and do not supply sensitive information about the system.

## Related weaknesses

- CWE-756 (ChildOf)

## Source

- [CWE-7 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/7.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
