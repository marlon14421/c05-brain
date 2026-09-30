---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1192"
target_object: "T1070.004"
stix_relationship_id: "relationship--76f024b3-69e2-4f1e-9b57-b81b871c3acb"
---
# Relationship 3039: S1192 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1192 - NICECURL|S1192: NICECURL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NICECURL](https://attack.mitre.org/software/S1192) has a function to remove artifacts.(Citation: Mandiant APT42-untangling)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76f024b3-69e2-4f1e-9b57-b81b871c3acb`.
