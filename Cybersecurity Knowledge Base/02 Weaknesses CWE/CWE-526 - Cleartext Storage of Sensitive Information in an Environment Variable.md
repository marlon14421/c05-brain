---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-526"
status: "Incomplete"
---
# CWE-526: Cleartext Storage of Sensitive Information in an Environment Variable

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses an environment variable to store unencrypted sensitive information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Encrypt information stored in the environment variable to protect it from being exposed to an unauthorized user. If encryption is not feasible or is considered too expensive for the business use of the application, then consider using a properly protected configuration file instead of an environment variable. It should be understood that unencrypted information in a config file is also not guaranteed to be protected, but it is still a better choice, because it reduces attack surface related to weaknesses such as CWE-214. In some settings, vaults might be a feasible option for safer data transfer. Users should be notified of the business choice made to not protect the sensitive information through encryption.
- **Implementation:** If the environment variable is not necessary for the desired behavior, then remove it entirely, or clear it to an empty value.

## Related weaknesses

- CWE-312 (ChildOf)
- CWE-214 (PeerOf)

## Source

- [CWE-526 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/526.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
