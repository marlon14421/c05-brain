---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1300"
status: "Stable"
---
# CWE-1300: Improper Protection of Physical Side Channels

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The device does not contain sufficient protection mechanisms to prevent physical side channels from exposing sensitive information due to patterns in physically observable phenomena such as variations in power consumption, electromagnetic emissions (EME), or acoustic emissions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Apply blinding or masking techniques to implementations of cryptographic algorithms.
- **Implementation:** Add shielding or tamper-resistant protections to the device to increase the difficulty of obtaining measurements of the side-channel.

## Related weaknesses

- CWE-203 (ChildOf)
- CWE-203 (ChildOf)

## Source

- [CWE-1300 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1300.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
