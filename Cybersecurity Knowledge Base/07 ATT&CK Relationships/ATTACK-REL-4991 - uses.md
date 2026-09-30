---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0060"
target_object: "T1137.001"
stix_relationship_id: "relationship--c3d716d9-a94d-49a7-af66-0166d9fe1f58"
---
# Relationship 4991: C0060 — uses → T1137.001

**Source object:** [[01 ATT&CK/C0060 - Operation AkaiRyū|C0060: Operation AkaiRyū]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1137.001 - Office Template Macros|T1137.001: Office Template Macros]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation AkaiRyū](https://attack.mitre.org/campaigns/C0060), [MirrorFace](https://attack.mitre.org/groups/G1054) loaded malicious Word templates containing VBA code leading to installation of [UPPERCUT](https://attack.mitre.org/software/S0275).(Citation: ESET MirrorFace 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c3d716d9-a94d-49a7-af66-0166d9fe1f58`.
