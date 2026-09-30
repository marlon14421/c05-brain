---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0603"
target_object: "T1570"
stix_relationship_id: "relationship--da63f54a-e6a4-414b-9d54-404b0a63d2f6"
---
# Relationship 3779: S0603 — uses → T1570

**Source object:** [[01 ATT&CK/S0603 - Stuxnet|S0603: Stuxnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Stuxnet](https://attack.mitre.org/software/S0603) uses an RPC server that contains a file dropping routine and support for payload version updates for P2P communications within a victim network.(Citation: Nicolas Falliere, Liam O Murchu, Eric Chien February 2011)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--da63f54a-e6a4-414b-9d54-404b0a63d2f6`.
