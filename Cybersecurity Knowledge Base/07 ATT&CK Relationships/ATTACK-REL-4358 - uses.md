---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1170"
target_object: "T1083"
stix_relationship_id: "relationship--9105b1f2-17a4-4c2c-9ec9-3bff60b0b898"
---
# Relationship 4358: S1170 — uses → T1083

**Source object:** [[01 ATT&CK/S1170 - ODAgent|S1170: ODAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ODAgent](https://attack.mitre.org/software/S1170) can identify the current working directory.(Citation: ESET OilRig Downloaders DEC 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9105b1f2-17a4-4c2c-9ec9-3bff60b0b898`.
