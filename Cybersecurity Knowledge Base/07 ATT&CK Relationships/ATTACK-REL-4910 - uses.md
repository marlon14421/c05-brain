---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1145"
target_object: "T1016"
stix_relationship_id: "relationship--05381a55-01d2-4c75-9a2b-504eff1b606a"
---
# Relationship 4910: S1145 — uses → T1016

**Source object:** [[01 ATT&CK/S1145 - Pikabot|S1145: Pikabot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pikabot](https://attack.mitre.org/software/S1145) gathers victim network information through commands such as ipconfig and ipconfig /all .(Citation: Zscaler Pikabot 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05381a55-01d2-4c75-9a2b-504eff1b606a`.
