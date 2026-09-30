---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-170"
status: "Incomplete"
---
# CWE-170: Improper Null Termination

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

The product does not terminate or incorrectly terminates a string or array with a null character or equivalent terminator.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Use a language that is not susceptible to these issues. However, be careful of null byte interaction errors (CWE-626) with lower-level constructs that may be written in a language that is susceptible.
- **Implementation:** Ensure that all string functions used are understood fully as to how they append null characters. Also, be wary of off-by-one errors when appending nulls to the end of strings.
- **Implementation:** If performance constraints permit, special code can be added that validates null-termination of string buffers, this is a rather naive and error-prone solution.
- **Implementation:** Switch to bounded string manipulation functions. Inspect buffer lengths involved in the buffer overrun trace reported with the defect.
- **Implementation:** Add code that fills buffers with nulls (however, the length of buffers still needs to be inspected, to ensure that the non null-terminated string is not written at the physical end of the buffer).

## Related weaknesses

- CWE-707 (ChildOf)
- CWE-120 (CanPrecede)
- CWE-126 (CanPrecede)
- CWE-147 (CanAlsoBe)
- CWE-464 (PeerOf)
- CWE-463 (PeerOf)
- CWE-20 (ChildOf)

## Source

- [CWE-170 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/170.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
