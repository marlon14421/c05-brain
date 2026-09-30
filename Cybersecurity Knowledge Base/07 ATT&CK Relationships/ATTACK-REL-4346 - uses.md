---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0275"
target_object: "T1574.001"
stix_relationship_id: "relationship--3d4524b0-db14-41d1-bcf7-68fce4dca5cc"
---
# Relationship 4346: S0275 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0275 - UPPERCUT|S0275: UPPERCUT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[UPPERCUT](https://attack.mitre.org/software/S0275) has been sideloaded through a legitimately signed application from the JustSystems Corporation.(Citation: ESET MirrorFace 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d4524b0-db14-41d1-bcf7-68fce4dca5cc`.
