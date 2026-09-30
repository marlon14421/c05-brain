---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1322"
status: "Incomplete"
---
# CWE-1322: Use of Blocking Code in Single-threaded, Non-blocking Context

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses a non-blocking model that relies on a single threaded process for features such as scalability, but it contains code that can block when it is invoked.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Generally speaking, blocking calls should be replaced with non-blocking alternatives that can be used asynchronously. Expensive computations should be passed off to worker threads, although the correct approach depends on the framework being used.
- **Implementation:** For expensive computations, consider breaking them up into multiple smaller computations. Refer to the documentation of the framework being used for guidance.

## Related weaknesses

- CWE-834 (ChildOf)
- CWE-835 (CanPrecede)

## Source

- [CWE-1322 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1322.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
