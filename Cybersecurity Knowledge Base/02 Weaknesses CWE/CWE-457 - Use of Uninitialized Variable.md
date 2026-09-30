---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-457"
status: "Draft"
---
# CWE-457: Use of Uninitialized Variable

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Perl, PHP, Not Language-Specific

## Description

The code uses a variable that has not been initialized, leading to unpredictable or unintended results.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that critical variables are initialized before first use [REF-1485].
- **Build and Compilation:** Most compilers will complain about the use of uninitialized variables if warnings are turned on.
- **Implementation:** When using a language that does not require explicit declaration of variables, run or compile the software in a mode that reports undeclared or unknown variables. This may indicate the presence of a typographic error in the variable's name.
- **Requirements:** Choose a language that is not susceptible to these issues.
- **Architecture and Design:** Mitigating technologies such as safe string libraries and container abstractions could be introduced.

## Related weaknesses

- CWE-908 (ChildOf)
- CWE-665 (ChildOf)
- CWE-665 (ChildOf)

## Source

- [CWE-457 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/457.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
