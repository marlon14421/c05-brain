---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-595"
status: "Incomplete"
---
# CWE-595: Comparison of Object References Instead of Object Contents

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java, JavaScript, PHP, Not Language-Specific

## Description

The product compares object references instead of the contents of the objects themselves, preventing it from detecting equivalent objects.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** In Java, use the equals() method to compare objects instead of the == operator. If using ==, it is important for performance reasons that your objects are created by a static factory, not by a constructor.

## Related weaknesses

- CWE-1025 (ChildOf)

## Source

- [CWE-595 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/595.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
