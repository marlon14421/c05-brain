---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1166"
target_object: "T1070.004"
stix_relationship_id: "relationship--a14caa38-c5b5-4357-b1fb-b648a017d0de"
---
# Relationship 2657: S1166 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1166 - Solar|S1166: Solar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Solar](https://attack.mitre.org/software/S1166) has the ability to delete staged files after they are uploaded to C2.(Citation: ESET OilRig Campaigns Sep 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a14caa38-c5b5-4357-b1fb-b648a017d0de`.
