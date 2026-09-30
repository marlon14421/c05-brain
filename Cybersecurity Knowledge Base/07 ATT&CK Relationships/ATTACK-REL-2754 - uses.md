---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1012"
target_object: "T1584.006"
stix_relationship_id: "relationship--48e14644-3ca8-4280-977b-50a6808a707f"
---
# Relationship 2754: G1012 — uses → T1584.006

**Source object:** [[01 ATT&CK/G1012 - CURIUM|G1012: CURIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.006 - Web Services|T1584.006: Web Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CURIUM](https://attack.mitre.org/groups/G1012) has compromised legitimate websites to enable strategic website compromise attacks.(Citation: PWC Yellow Liderc 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48e14644-3ca8-4280-977b-50a6808a707f`.
