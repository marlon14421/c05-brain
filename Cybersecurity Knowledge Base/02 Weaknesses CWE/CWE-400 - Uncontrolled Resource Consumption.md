---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-400"
status: "Draft"
---
# CWE-400: Uncontrolled Resource Consumption

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, AI/ML

## Description

The product does not properly control the allocation and maintenance of a limited resource.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Design throttling mechanisms into the system architecture. The best protection is to limit the amount of resources that an unauthorized user can cause to be expended. A strong authentication and access control model will help prevent such attacks from occurring in the first place. The login application should be protected against DoS attacks as much as possible. Limiting the database access, perhaps by caching result sets, can help minimize the resources expended. To further limit the potential for a DoS attack, consider tracking the rate of requests received from users and blocking requests that exceed a defined rate threshold.
- **Architecture and Design:** Ensure that protocols have specific limits of scale placed on them.
- **Implementation:** Ensure that all failures in resource allocation place the system into a safe posture.

## Related weaknesses

- CWE-664 (ChildOf)

## Source

- [CWE-400 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/400.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
