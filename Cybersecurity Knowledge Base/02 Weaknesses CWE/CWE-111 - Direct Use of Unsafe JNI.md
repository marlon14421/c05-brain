---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-111"
status: "Draft"
---
# CWE-111: Direct Use of Unsafe JNI

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

When a Java application uses the Java Native Interface (JNI) to call code written in another programming language, it can expose the application to weaknesses in that code, even if those weaknesses cannot occur in Java.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Implement error handling around the JNI call.
- **Implementation:** Do not use JNI calls if you don't trust the native library.
- **Implementation:** Be reluctant to use JNI calls. A Java API equivalent may exist.

## Related weaknesses

- CWE-695 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-111 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/111.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
