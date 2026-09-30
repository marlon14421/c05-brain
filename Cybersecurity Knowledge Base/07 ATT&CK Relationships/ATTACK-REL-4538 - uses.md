---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1146"
target_object: "T1087.002"
stix_relationship_id: "relationship--18cccfc2-e5a7-41ca-93ad-4ffef966b50b"
---
# Relationship 4538: S1146 — uses → T1087.002

**Source object:** [[01 ATT&CK/S1146 - MgBot|S1146: MgBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MgBot](https://attack.mitre.org/software/S1146) includes modules for collecting information on Active Directory domain accounts.(Citation: Symantec Daggerfly 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18cccfc2-e5a7-41ca-93ad-4ffef966b50b`.
