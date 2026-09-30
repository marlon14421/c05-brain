---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0012"
target_object: "T1091"
stix_relationship_id: "relationship--5bad7b38-36b5-4208-9895-e4a113c511a3"
---
# Relationship 3181: G0012 — uses → T1091

**Source object:** [[01 ATT&CK/G0012 - Darkhotel|G0012: Darkhotel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1091 - Replication Through Removable Media|T1091: Replication Through Removable Media]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Darkhotel](https://attack.mitre.org/groups/G0012)'s selective infector modifies executables stored on removable media as a method of spreading across computers.(Citation: Kaspersky Darkhotel)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5bad7b38-36b5-4208-9895-e4a113c511a3`.
