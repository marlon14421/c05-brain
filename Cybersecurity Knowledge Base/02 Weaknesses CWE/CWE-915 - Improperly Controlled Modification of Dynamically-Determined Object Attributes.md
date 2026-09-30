---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-915"
status: "Incomplete"
---
# CWE-915: Improperly Controlled Modification of Dynamically-Determined Object Attributes

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Ruby, ASP.NET, PHP, Python, Not Language-Specific, Not Technology-Specific

## Description

The product receives input from an upstream component that specifies multiple attributes, properties, or fields that are to be initialized or updated in an object, but it does not properly control which attributes can be modified.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** If available, use the signing/sealing features of the programming language to assure that deserialized data has not been tainted. For example, a hash-based message authentication code (HMAC) could be used to ensure that data has not been modified.
- **Implementation:** For any externally-influenced input, check the input against an allowlist of internal object attributes or fields that are allowed to be modified.
- **Implementation:** Refactor the code so that object attributes or fields do not need to be dynamically identified, and only expose getter/setter functionality for the intended attributes.

## Related weaknesses

- CWE-913 (ChildOf)
- CWE-502 (PeerOf)

## Source

- [CWE-915 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/915.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
