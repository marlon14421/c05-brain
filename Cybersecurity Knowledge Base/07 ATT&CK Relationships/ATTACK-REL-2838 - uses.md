---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1183"
target_object: "T1518"
stix_relationship_id: "relationship--5166f101-8d87-4967-bc3c-5f6ee97b863c"
---
# Relationship 2838: S1183 — uses → T1518

**Source object:** [[01 ATT&CK/S1183 - StrelaStealer|S1183: StrelaStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) variants use COM objects to enumerate installed applications from the "AppsFolder" on victim machines.(Citation: IBM StrelaStealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5166f101-8d87-4967-bc3c-5f6ee97b863c`.
