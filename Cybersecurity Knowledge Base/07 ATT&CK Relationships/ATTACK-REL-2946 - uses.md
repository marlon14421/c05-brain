---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1074"
target_object: "T1036.008"
stix_relationship_id: "relationship--84b29e13-6577-4db2-846c-a42caf068cb8"
---
# Relationship 2946: S1074 — uses → T1036.008

**Source object:** [[01 ATT&CK/S1074 - ANDROMEDA|S1074: ANDROMEDA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.008 - Masquerade File Type|T1036.008: Masquerade File Type]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ANDROMEDA](https://attack.mitre.org/software/S1074) has been delivered through a LNK file disguised as a folder.(Citation: Mandiant Suspected Turla Campaign February 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84b29e13-6577-4db2-846c-a42caf068cb8`.
