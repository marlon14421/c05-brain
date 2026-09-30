---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1065"
target_object: "T1113"
stix_relationship_id: "relationship--85fda77f-5129-4de7-bc44-f81ccc46f6d9"
---
# Relationship 3621: S1065 — uses → T1113

**Source object:** [[01 ATT&CK/S1065 - Woody RAT|S1065: Woody RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Woody RAT](https://attack.mitre.org/software/S1065) has the ability to take a screenshot of the infected host desktop using Windows GDI+.(Citation: MalwareBytes WoodyRAT Aug 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85fda77f-5129-4de7-bc44-f81ccc46f6d9`.
