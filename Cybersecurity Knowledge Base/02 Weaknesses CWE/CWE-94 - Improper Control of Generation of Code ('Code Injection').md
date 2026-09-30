---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-94"
status: "Draft"
---
# CWE-94: Improper Control of Generation of Code ('Code Injection')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Interpreted, AI/ML

## Description

The product constructs all or part of a code segment using externally-influenced input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could modify the syntax or behavior of the intended code segment.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Refactor your program so that you do not have to dynamically generate code.
- **Testing:** Use dynamic tools and techniques that interact with the product using large test suites with many diverse inputs, such as fuzz testing (fuzzing), robustness testing, and fault injection. The product's operation may slow down, but it should not become unstable, crash, or generate incorrect results.
- **Operation:** Run the code in an environment that performs automatic taint propagation and prevents any command execution that uses tainted variables, such as Perl's "-T" switch. This will force the program to perform validation steps that remove the taint, although you must be careful to correctly validate your inputs so that you do not accidentally mark dangerous inputs as untainted (see CWE-183 and CWE-184).
- **Operation:** Run the code in an environment that performs automatic taint propagation and prevents any command execution that uses tainted variables, such as Perl's "-T" switch. This will force the program to perform validation steps that remove the taint, although you must be careful to correctly validate your inputs so that you do not accidentally mark dangerous inputs as untainted (see CWE-183 and CWE-184).

## Related weaknesses

- CWE-74 (ChildOf)
- CWE-74 (ChildOf)
- CWE-913 (ChildOf)

## Source

- [CWE-94 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/94.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
