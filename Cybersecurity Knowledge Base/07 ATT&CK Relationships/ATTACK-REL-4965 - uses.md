---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1571"
stix_relationship_id: "relationship--c5692c9d-8cac-4105-ae0b-f3b6c60a2253"
---
# Relationship 4965: S0013 — uses → T1571

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) has used random, high-number, non-standard ports to listen for subsequent actions and C2 activities.(Citation: Sygnia VelvetAnt 2024A)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5692c9d-8cac-4105-ae0b-f3b6c60a2253`.
