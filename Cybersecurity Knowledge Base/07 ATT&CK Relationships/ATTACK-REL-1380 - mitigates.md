---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1092"
stix_relationship_id: "relationship--c4b3287c-5e5a-4ec0-bc20-4e3b6a0c296f"
---
# Relationship 1380: M1028 — mitigates → T1092

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1092 - Communication Through Removable Media|T1092: Communication Through Removable Media]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Disallow or restrict removable media at an organizational policy level if they are not required for business operations.(Citation: TechNet Removable Media Control)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4b3287c-5e5a-4ec0-bc20-4e3b6a0c296f`.
