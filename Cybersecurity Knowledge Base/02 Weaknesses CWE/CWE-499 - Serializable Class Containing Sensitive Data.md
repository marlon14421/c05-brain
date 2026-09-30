---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-499"
status: "Draft"
---
# CWE-499: Serializable Class Containing Sensitive Data

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The code contains a class with sensitive data, but the class does not explicitly deny serialization. The data can be accessed by serializing the class through another class.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** In Java, explicitly define final writeObject() to prevent serialization. This is the recommended solution. Define the writeObject() function to throw an exception explicitly denying serialization.
- **Implementation:** Make sure to prevent serialization of your objects.

## Related weaknesses

- CWE-668 (ChildOf)
- CWE-200 (CanPrecede)

## Source

- [CWE-499 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/499.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
