---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1538"
stix_relationship_id: "relationship--450571d1-ce87-4017-bdc8-30fb2b6ae852"
---
# Relationship 4038: G1015 — uses → T1538

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1538 - Cloud Service Dashboard|T1538: Cloud Service Dashboard]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) abused AWS Systems Manager Inventory to identify targets on the compromised network prior to lateral movement.(Citation: CISA Scattered Spider Advisory November 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--450571d1-ce87-4017-bdc8-30fb2b6ae852`.
