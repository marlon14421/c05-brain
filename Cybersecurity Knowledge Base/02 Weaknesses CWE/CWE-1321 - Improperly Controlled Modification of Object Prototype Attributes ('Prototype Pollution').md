---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1321"
status: "Incomplete"
---
# CWE-1321: Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** JavaScript

## Description

The product receives input from an upstream component that specifies attributes that are to be initialized or updated in an object, but it does not properly control modifications of attributes of the object prototype.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** By freezing the object prototype first (for example, Object.freeze(Object.prototype)), modification of the prototype becomes impossible.
- **Architecture and Design:** By blocking modifications of attributes that resolve to object prototype, such as proto or prototype, this weakness can be mitigated.
- **Implementation:** When handling untrusted objects, validating using a schema can be used.
- **Implementation:** By using an object without prototypes (via Object.create(null) ), adding object prototype attributes by accessing the prototype via the special attributes becomes impossible, mitigating this weakness.
- **Implementation:** Map can be used instead of objects in most cases. If Map methods are used instead of object attributes, it is not possible to access the object prototype or modify it.

## Related weaknesses

- CWE-915 (ChildOf)
- CWE-913 (ChildOf)
- CWE-471 (CanPrecede)

## Source

- [CWE-1321 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1321.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
