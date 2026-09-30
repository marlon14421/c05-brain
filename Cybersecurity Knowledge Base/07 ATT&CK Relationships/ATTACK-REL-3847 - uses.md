---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1190"
target_object: "T1053.005"
stix_relationship_id: "relationship--6884d485-5ec1-46ab-b36d-ab11567f38fc"
---
# Relationship 3847: S1190 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1190 - Kapeka|S1190: Kapeka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kapeka](https://attack.mitre.org/software/S1190) persists via scheduled tasks.(Citation: Microsoft KnuckleTouch 2024)(Citation: WithSecure Kapeka 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6884d485-5ec1-46ab-b36d-ab11567f38fc`.
