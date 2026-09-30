---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1013"
target_object: "T1564"
stix_relationship_id: "relationship--508cef53-f7ff-4e64-9ab3-dedefbba697b"
---
# Relationship 0257: M1013 — mitigates → T1564

**Source object:** [[01 ATT&CK/M1013 - Application Developer Guidance|M1013: Application Developer Guidance]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1564 - Hide Artifacts|T1564: Hide Artifacts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Application developers should consider limiting the requirements for custom or otherwise difficult to manage file/folder exclusions. Where possible, install applications to trusted system folder paths that are already protected by restricted file and directory permissions.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--508cef53-f7ff-4e64-9ab3-dedefbba697b`.
