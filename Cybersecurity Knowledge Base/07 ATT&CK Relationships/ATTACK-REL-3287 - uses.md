---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0414"
target_object: "T1083"
stix_relationship_id: "relationship--5c738353-868a-4e4d-8628-e1d14e502980"
---
# Relationship 3287: S0414 — uses → T1083

**Source object:** [[01 ATT&CK/S0414 - BabyShark|S0414: BabyShark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BabyShark](https://attack.mitre.org/software/S0414) has used dir to search for "programfiles" and "appdata".(Citation: Unit42 BabyShark Feb 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c738353-868a-4e4d-8628-e1d14e502980`.
