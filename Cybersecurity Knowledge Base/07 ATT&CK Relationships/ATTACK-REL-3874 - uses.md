---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0061"
target_object: "S0097"
stix_relationship_id: "relationship--201802a3-afae-4c10-a125-0fc4fd62f1d2"
---
# Relationship 3874: G0061 — uses → S0097

**Source object:** [[01 ATT&CK/G0061 - FIN8|G0061: FIN8]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0097 - Ping|S0097: Ping]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Bitdefender Sardonic Aug 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--201802a3-afae-4c10-a125-0fc4fd62f1d2`.
