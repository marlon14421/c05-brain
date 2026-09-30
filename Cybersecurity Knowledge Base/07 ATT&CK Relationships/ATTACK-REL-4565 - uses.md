---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1125"
stix_relationship_id: "relationship--cfd35b85-8048-4c8f-9176-603744eecfce"
---
# Relationship 4565: G1055 — uses → T1125

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has collected video from compromised victim devices.(Citation: FBI IC3 Flash VOID MANTICORE Handala Hack March 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfd35b85-8048-4c8f-9176-603744eecfce`.
