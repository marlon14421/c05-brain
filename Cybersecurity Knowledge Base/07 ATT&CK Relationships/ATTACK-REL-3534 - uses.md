---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1044"
target_object: "T1119"
stix_relationship_id: "relationship--8f7fe970-0a16-4007-84ae-e7294d06595f"
---
# Relationship 3534: S1044 — uses → T1119

**Source object:** [[01 ATT&CK/S1044 - FunnyDream|S1044: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FunnyDream](https://attack.mitre.org/software/S1044) can monitor files for changes and automatically collect them.(Citation: Bitdefender FunnyDream Campaign November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f7fe970-0a16-4007-84ae-e7294d06595f`.
