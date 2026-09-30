---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1236"
target_object: "T1027.007"
stix_relationship_id: "relationship--fcb42350-a01d-46f7-b172-cd327f61061c"
---
# Relationship 4188: S1236 — uses → T1027.007

**Source object:** [[01 ATT&CK/S1236 - CLAIMLOADER|S1236: CLAIMLOADER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.007 - Dynamic API Resolution|T1027.007: Dynamic API Resolution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CLAIMLOADER](https://attack.mitre.org/software/S1236) has utilized XOR-encrypted API names and native APIs of `LdrLoadDll()` and `LderGetProcedureAddress()` to resolve imports dynamically.(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fcb42350-a01d-46f7-b172-cd327f61061c`.
