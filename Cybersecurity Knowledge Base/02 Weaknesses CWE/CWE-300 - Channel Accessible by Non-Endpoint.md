---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-300"
status: "Draft"
---
# CWE-300: Channel Accessible by Non-Endpoint

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not adequately verify the identity of actors at both ends of a communication channel, or does not adequately ensure the integrity of the channel, in a way that allows the channel to be accessed or influenced by an actor that is not an endpoint.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Always fully authenticate both ends of any communications channel.
- **Architecture and Design:** Adhere to the principle of complete mediation.
- **Implementation:** A certificate binds an identity to a cryptographic key to authenticate a communicating party. Often, the certificate takes the encrypted form of the hash of the identity of the subject, the public key, and information such as time of issue or expiration using the issuer's private key. The certificate can be validated by deciphering the certificate with the issuer's public key. See also X.509 certificate signature chains and the PGP certification structure.

## Related weaknesses

- CWE-923 (ChildOf)

## Source

- [CWE-300 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/300.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
