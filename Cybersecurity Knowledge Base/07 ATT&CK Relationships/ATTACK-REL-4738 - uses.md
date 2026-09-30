---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0467"
target_object: "T1083"
stix_relationship_id: "relationship--bfd1c3ca-ea2c-4b0e-8b0a-815b8ebb4dfb"
---
# Relationship 4738: S0467 — uses → T1083

**Source object:** [[01 ATT&CK/S0467 - TajMahal|S0467: TajMahal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TajMahal](https://attack.mitre.org/software/S0467) has the ability to index files from drives, user profiles, and removable drives.(Citation: Kaspersky TajMahal April 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfd1c3ca-ea2c-4b0e-8b0a-815b8ebb4dfb`.
