---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1039"
target_object: "T1012"
stix_relationship_id: "relationship--acbf0f3f-5dd4-42ad-9399-047b8ff5dc0a"
---
# Relationship 4699: S1039 — uses → T1012

**Source object:** [[01 ATT&CK/S1039 - Bumblebee|S1039: Bumblebee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bumblebee](https://attack.mitre.org/software/S1039) can check the Registry for specific keys.(Citation: Medium Ali Salem Bumblebee April 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--acbf0f3f-5dd4-42ad-9399-047b8ff5dc0a`.
