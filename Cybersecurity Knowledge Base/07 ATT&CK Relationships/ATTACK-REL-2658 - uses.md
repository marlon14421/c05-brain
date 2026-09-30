---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0495"
target_object: "T1113"
stix_relationship_id: "relationship--49d50fde-cfbc-4007-befc-f4b22b9bc9f5"
---
# Relationship 2658: S0495 — uses → T1113

**Source object:** [[01 ATT&CK/S0495 - RDAT|S0495: RDAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RDAT](https://attack.mitre.org/software/S0495) can take a screenshot on the infected system.(Citation: Unit42 RDAT July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49d50fde-cfbc-4007-befc-f4b22b9bc9f5`.
