---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1183"
target_object: "T1027.015"
stix_relationship_id: "relationship--7522bc84-384e-497f-8898-196283ba5ec1"
---
# Relationship 4128: S1183 — uses → T1027.015

**Source object:** [[01 ATT&CK/S1183 - StrelaStealer|S1183: StrelaStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) has been delivered via JScript files in a ZIP archive.(Citation: PaloAlto StrelaStealer 2024)(Citation: Fortgale StrelaStealer 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7522bc84-384e-497f-8898-196283ba5ec1`.
