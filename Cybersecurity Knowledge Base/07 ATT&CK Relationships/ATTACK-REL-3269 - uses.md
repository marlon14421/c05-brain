---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1181"
target_object: "T1070.004"
stix_relationship_id: "relationship--c6574b3a-e4f4-4528-aa61-ad3db800a259"
---
# Relationship 3269: S1181 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1181 - BlackByte 2.0 Ransomware|S1181: BlackByte 2.0 Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) deletes itself following device encryption.(Citation: Microsoft BlackByte 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6574b3a-e4f4-4528-aa61-ad3db800a259`.
