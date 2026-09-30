---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-926"
status: "Incomplete"
---
# CWE-926: Improper Export of Android Application Components

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Mobile

## Description

The Android application exports a component for use by other applications, but does not properly restrict which applications can launch the component or access the data it contains.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Build and Compilation:** If they do not need to be shared by other applications, explicitly mark components with android:exported="false" in the application manifest.
- **Build and Compilation:** If you only intend to use exported components between related apps under your control, use android:protectionLevel="signature" in the xml manifest to restrict access to applications signed by you.
- **Build and Compilation:** Limit Content Provider permissions (read/write) as appropriate.
- **Build and Compilation:** Limit Content Provider permissions (read/write) as appropriate.

## Related weaknesses

- CWE-285 (ChildOf)

## Source

- [CWE-926 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/926.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
