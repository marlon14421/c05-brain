---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-367"
status: "Incomplete"
---
# CWE-367: Time-of-check Time-of-use (TOCTOU) Race Condition

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product checks the state of a resource before using that resource, but the resource's state can change between the check and the use in a way that invalidates the results of the check.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** The most basic advice for TOCTOU vulnerabilities is to not perform a check before the use. This does not resolve the underlying issue of the execution of a function on a resource whose state and identity cannot be assured, but it does help to limit the false sense of security given by the check.
- **Implementation:** When the file being altered is owned by the current user and group, set the effective gid and uid to that of the current user and group when executing this statement.
- **Architecture and Design:** Limit the interleaving of operations on files from multiple processes.
- **Implementation:** If you cannot perform operations atomically and you must share access to the resource between multiple processes or threads, then try to limit the amount of time (CPU cycles) between the check and use of the resource. This will not fix the problem, but it could make it more difficult for an attack to succeed.
- **Implementation:** Recheck the resource after the use call to verify that the action was taken appropriately.
- **Architecture and Design:** Ensure that some environmental locking mechanism can be used to protect resources effectively.
- **Implementation:** Ensure that locking occurs before the check, as opposed to afterwards, such that the resource, as checked, is the same as it is when in use.

## Related weaknesses

- CWE-362 (ChildOf)
- CWE-362 (ChildOf)

## Source

- [CWE-367 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/367.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
