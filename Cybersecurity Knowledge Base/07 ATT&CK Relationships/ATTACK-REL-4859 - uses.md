---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1072"
target_object: "T1057"
stix_relationship_id: "relationship--849c40ae-9dc7-4861-9a6c-8c03b4ffb7b5"
---
# Relationship 4859: S1072 — uses → T1057

**Source object:** [[01 ATT&CK/S1072 - Industroyer2|S1072: Industroyer2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Industroyer2](https://attack.mitre.org/software/S1072) has the ability to cyclically enumerate running processes such as PServiceControl.exe, PService_PDD.exe, and other targets supplied through a hardcoded configuration.(Citation: Industroyer2 Mandiant April 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--849c40ae-9dc7-4861-9a6c-8c03b4ffb7b5`.
