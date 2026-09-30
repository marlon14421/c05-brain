---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1181"
target_object: "T1112"
stix_relationship_id: "relationship--40b51ac6-d391-4fcb-ae32-79705d25301a"
---
# Relationship 3140: S1181 — uses → T1112

**Source object:** [[01 ATT&CK/S1181 - BlackByte 2.0 Ransomware|S1181: BlackByte 2.0 Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) modifies the victim Registry to allow for elevated execution.(Citation: Microsoft BlackByte 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--40b51ac6-d391-4fcb-ae32-79705d25301a`.
