---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1580"
stix_relationship_id: "relationship--0cc93ab3-094a-46f4-921c-486824dcf78f"
---
# Relationship 2925: S9041 — uses → T1580

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1580 - Cloud Infrastructure Discovery|T1580: Cloud Infrastructure Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) has the ability to search for generic GitHub runners.(Citation: Wiz TeamPCP KICS MAR 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cc93ab3-094a-46f4-921c-486824dcf78f`.
