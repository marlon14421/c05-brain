---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1167"
target_object: "T1070.004"
stix_relationship_id: "relationship--e833d684-ee9f-43f7-977b-3d2939951c12"
---
# Relationship 2757: S1167 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1167 - AcidPour|S1167: AcidPour]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AcidPour](https://attack.mitre.org/software/S1167) includes a self-delete function where the malware deletes itself from disk after execution and program load into memory.(Citation: SentinelOne AcidPour 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e833d684-ee9f-43f7-977b-3d2939951c12`.
