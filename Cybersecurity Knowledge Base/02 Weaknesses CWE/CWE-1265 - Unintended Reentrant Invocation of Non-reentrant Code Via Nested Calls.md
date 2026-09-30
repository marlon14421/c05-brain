---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1265"
status: "Draft"
---
# CWE-1265: Unintended Reentrant Invocation of Non-reentrant Code Via Nested Calls

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product invokes code that is believed to be reentrant, but the code performs a call that unintentionally produces a nested invocation of the non-reentrant code.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When architecting a system that will execute untrusted code in response to events, consider executing the untrusted event handlers asynchronously (asynchronous message passing) as opposed to executing them synchronously at the time each event fires. The untrusted code should execute at the start of the next iteration of the thread's message loop. In this way, calls into non-reentrant code are strictly serialized, so that each operation completes fully before the next operation begins. Special attention must be paid to all places where type coercion may result in script execution. Performing all needed coercions at the very beginning of an operation can help reduce the chance of operations executing at unexpected junctures.
- **Implementation:** Make sure the code (e.g., function or class) in question is reentrant by not leveraging non-local data, not modifying its own code, and not calling other non-reentrant code.

## Related weaknesses

- CWE-662 (ChildOf)
- CWE-663 (PeerOf)
- CWE-416 (CanPrecede)

## Source

- [CWE-1265 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1265.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
