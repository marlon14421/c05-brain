---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0098"
target_object: "S0029"
stix_relationship_id: "relationship--36f159f7-5018-4889-a540-98e3ac242602"
---
# Relationship 3354: G0098 — uses → S0029

**Source object:** [[01 ATT&CK/G0098 - BlackTech|G0098: BlackTech]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Symantec Palmerworm Sep 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36f159f7-5018-4889-a540-98e3ac242602`.
