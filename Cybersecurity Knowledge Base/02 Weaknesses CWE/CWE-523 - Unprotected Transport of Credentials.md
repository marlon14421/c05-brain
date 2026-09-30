---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-523"
status: "Incomplete"
---
# CWE-523: Unprotected Transport of Credentials

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

Login pages do not use adequate measures to protect the user name and password while they are in transit from the client to the server.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Operation:** Enforce SSL use for the login page or any page used to transmit user credentials or other sensitive information. Even if the entire site does not use SSL, it MUST use SSL for login. Additionally, to help prevent phishing attacks, make sure that SSL serves the login page. SSL allows the user to verify the identity of the server to which they are connecting. If the SSL serves login page, the user can be certain they are talking to the proper end system. A phishing attack would typically redirect a user to a site that does not have a valid trusted server certificate issued from an authorized supplier.

## Related weaknesses

- CWE-522 (ChildOf)
- CWE-319 (CanAlsoBe)

## Source

- [CWE-523 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/523.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
