---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0414"
target_object: "T1016"
stix_relationship_id: "relationship--cef53316-353b-48f8-bce4-1d95f3ff843e"
---
# Relationship 3420: S0414 — uses → T1016

**Source object:** [[01 ATT&CK/S0414 - BabyShark|S0414: BabyShark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BabyShark](https://attack.mitre.org/software/S0414) has executed the ipconfig /all command.(Citation: Unit42 BabyShark Feb 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cef53316-353b-48f8-bce4-1d95f3ff843e`.
